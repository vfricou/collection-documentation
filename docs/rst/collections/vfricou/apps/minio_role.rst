.. Document meta

:orphan:

.. |antsibull-internal-nbsp| unicode:: 0xA0
    :trim:

.. meta::
  :antsibull-docs: 2.16.3

.. Anchors

.. _ansible_collections.vfricou.apps.minio_role:

.. Title

vfricou.apps.minio role -- Install and configure Minio standalone
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. Collection note

.. note::
    This role is part of the `vfricou.apps collection <https://galaxy.ansible.com/ui/repo/published/vfricou/apps/>`_ (version 1.0.0).

    It is not included in ``ansible-core``.
    To check whether it is installed, run :code:`ansible-galaxy collection list`.

    To install it use: :code:`ansible-galaxy collection install vfricou.apps`.

    To use it in a playbook, specify: :code:`vfricou.apps.minio`.

.. contents::
   :local:
   :depth: 2


.. Entry point title

Entry point ``main`` -- Install and configure Minio standalone
--------------------------------------------------------------

.. version_added


.. Deprecated


Synopsis
^^^^^^^^

.. Description

- Install Minio
- Configure Minio server as standalone instance

.. Requirements


.. Options

Parameters
^^^^^^^^^^

.. tabularcolumns:: \X{1}{3}\X{2}{3}

.. list-table::
  :width: 100%
  :widths: auto
  :header-rows: 1
  :class: longtable ansible-option-table

  * - Parameter
    - Comments

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--minio_admin_password"></div>

      .. _ansible_collections.vfricou.apps.minio_role__parameter-main__minio_admin_password:

      .. rst-class:: ansible-option-title

      **minio_admin_password**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--minio_admin_password" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string` / :ansible-option-required:`required`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Minio admin account password


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--minio_admin_username"></div>

      .. _ansible_collections.vfricou.apps.minio_role__parameter-main__minio_admin_username:

      .. rst-class:: ansible-option-title

      **minio_admin_username**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--minio_admin_username" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string` / :ansible-option-required:`required`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Minio admin account username


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--minio_base_path"></div>

      .. _ansible_collections.vfricou.apps.minio_role__parameter-main__minio_base_path:

      .. rst-class:: ansible-option-title

      **minio_base_path**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--minio_base_path" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Minio operations base path


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"/opt/minio"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--minio_bind_address"></div>

      .. _ansible_collections.vfricou.apps.minio_role__parameter-main__minio_bind_address:

      .. rst-class:: ansible-option-title

      **minio_bind_address**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--minio_bind_address" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Minio bind address


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"0.0.0.0"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--minio_bind_port"></div>

      .. _ansible_collections.vfricou.apps.minio_role__parameter-main__minio_bind_port:

      .. rst-class:: ansible-option-title

      **minio_bind_port**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--minio_bind_port" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Minio bind port


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`9000`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--minio_console_bind_address"></div>

      .. _ansible_collections.vfricou.apps.minio_role__parameter-main__minio_console_bind_address:

      .. rst-class:: ansible-option-title

      **minio_console_bind_address**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--minio_console_bind_address" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Minio Console bind address


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"0.0.0.0"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--minio_console_bind_port"></div>

      .. _ansible_collections.vfricou.apps.minio_role__parameter-main__minio_console_bind_port:

      .. rst-class:: ansible-option-title

      **minio_console_bind_port**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--minio_console_bind_port" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Minio Console bind port


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`9001`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--minio_dl_url"></div>

      .. _ansible_collections.vfricou.apps.minio_role__parameter-main__minio_dl_url:

      .. rst-class:: ansible-option-title

      **minio_dl_url**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--minio_dl_url" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Specify exact URL where retreive Minio binary file


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--minio_group"></div>

      .. _ansible_collections.vfricou.apps.minio_role__parameter-main__minio_group:

      .. rst-class:: ansible-option-title

      **minio_group**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--minio_group" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      System group run minio


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"minio"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--minio_no_log"></div>

      .. _ansible_collections.vfricou.apps.minio_role__parameter-main__minio_no_log:

      .. rst-class:: ansible-option-title

      **minio_no_log**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--minio_no_log" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Enable or disable :literal:`no\_log` directive


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry:`false`
      - :ansible-option-choices-entry-default:`true` :ansible-option-choices-default-mark:`← (default)`


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--minio_user"></div>

      .. _ansible_collections.vfricou.apps.minio_role__parameter-main__minio_user:

      .. rst-class:: ansible-option-title

      **minio_user**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--minio_user" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      System user run minio


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"minio"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--minio_version"></div>

      .. _ansible_collections.vfricou.apps.minio_role__parameter-main__minio_version:

      .. rst-class:: ansible-option-title

      **minio_version**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--minio_version" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Minio version

      :literal:`latest` specify latest available version in \ `Minio repository <https://dl.min.io/server/minio/release/linux-amd64/>`__

      You could install specific minio version with format :strong:`ERROR while parsing`\ : While parsing "C(YYYY-MM-DDTHH-MM-SSZ" at index 54: Cannot find closing ")" after last parameter

      Get version from \ `Minio repository <https://dl.min.io/server/minio/release/linux-amd64/>`__ for current version

      Get older version from \ `Minio archive repository <https://dl.min.io/server/minio/release/linux-amd64/archive>`__


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"latest"`

      .. raw:: html

        </div>


.. Attributes


.. Notes


.. Seealso


Examples
^^^^^^^^

.. code-block:: yaml+jinja

    # Playbook minio deployment
    ---
    - name: 'Minio'
      hosts:
        - s3
      vars:
        minio_admin_username: '<vaulted_minio_admin_username>'
        minio_admin_password: '<vaulted_minio_admin_password>'
      roles:
        - role: vfricou.apps.minio
          vars:
            minio_admin_username: "{{ __vault_minio_datas.data.data.username }}"
            minio_admin_password: "{{ __vault_minio_datas.data.data.password }}"


Authors
^^^^^^^

- Vincent FRICOU



.. Extra links

Collection links
~~~~~~~~~~~~~~~~

.. ansible-links::

  - title: "Issue Tracker"
    url: "https://github.com/vfricou/vfricou.apps/issues"
    external: true
  - title: "Repository (Sources)"
    url: "https://github.com/vfricou/vfricou.apps/"
    external: true


.. Parsing errors
