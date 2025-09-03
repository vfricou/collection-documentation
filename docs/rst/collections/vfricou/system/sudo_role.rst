.. Document meta

:orphan:

.. |antsibull-internal-nbsp| unicode:: 0xA0
    :trim:

.. meta::
  :antsibull-docs: 2.16.3

.. Anchors

.. _ansible_collections.vfricou.system.sudo_role:

.. Title

vfricou.system.sudo role -- Sudo configuration
++++++++++++++++++++++++++++++++++++++++++++++

.. Collection note

.. note::
    This role is part of the `vfricou.system collection <https://galaxy.ansible.com/ui/repo/published/vfricou/system/>`_ (version 1.0.0).

    It is not included in ``ansible-core``.
    To check whether it is installed, run :code:`ansible-galaxy collection list`.

    To install it use: :code:`ansible-galaxy collection install vfricou.system`.

    To use it in a playbook, specify: :code:`vfricou.system.sudo`.

.. contents::
   :local:
   :depth: 2


.. Entry point title

Entry point ``main`` -- Sudo configuration
------------------------------------------

.. version_added


.. Deprecated


Synopsis
^^^^^^^^

.. Description

- Configure sudo
- Configure sudoers

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
        <div class="ansibleOptionAnchor" id="parameter-main--sudo_extends"></div>

      .. _ansible_collections.vfricou.system.sudo_role__parameter-main__sudo_extends:

      .. rst-class:: ansible-option-title

      **sudo_extends**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--sudo_extends" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Sudo extended configurations


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--sudo_extends/content"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.vfricou.system.sudo_role__parameter-main__sudo_extends/content:

      .. rst-class:: ansible-option-title

      **content**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--sudo_extends/content" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string` / :ansible-option-required:`required`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Sudo configuration extends


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--sudo_extends/filename"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.vfricou.system.sudo_role__parameter-main__sudo_extends/filename:

      .. rst-class:: ansible-option-title

      **filename**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--sudo_extends/filename" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string` / :ansible-option-required:`required`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Configuration filename in :literal:`/etc/sudoers.d`


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--sudo_logfile"></div>

      .. _ansible_collections.vfricou.system.sudo_role__parameter-main__sudo_logfile:

      .. rst-class:: ansible-option-title

      **sudo_logfile**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--sudo_logfile" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Sudo action log file path


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"var/log/sudo.log"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--sudo_umask"></div>

      .. _ansible_collections.vfricou.system.sudo_role__parameter-main__sudo_umask:

      .. rst-class:: ansible-option-title

      **sudo_umask**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--sudo_umask" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Sudo UMask override


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"0027"`

      .. raw:: html

        </div>


.. Attributes


.. Notes


.. Seealso



Authors
^^^^^^^

- Vincent FRICOU



.. Extra links

Collection links
~~~~~~~~~~~~~~~~

.. ansible-links::

  - title: "Issue Tracker"
    url: "https://github.com/vfricou/vfricou.system/issues"
    external: true
  - title: "Repository (Sources)"
    url: "https://github.com/vfricou/vfricou.system/"
    external: true


.. Parsing errors
