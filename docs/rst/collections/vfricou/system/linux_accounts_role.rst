.. Document meta

:orphan:

.. |antsibull-internal-nbsp| unicode:: 0xA0
    :trim:

.. meta::
  :antsibull-docs: 2.16.3

.. Anchors

.. _ansible_collections.vfricou.system.linux_accounts_role:

.. Title

vfricou.system.linux_accounts role -- Manage accounts on GNU/Linux systems
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. Collection note

.. note::
    This role is part of the `vfricou.system collection <https://galaxy.ansible.com/ui/repo/published/vfricou/system/>`_ (version 1.0.0).

    It is not included in ``ansible-core``.
    To check whether it is installed, run :code:`ansible-galaxy collection list`.

    To install it use: :code:`ansible-galaxy collection install vfricou.system`.

    To use it in a playbook, specify: :code:`vfricou.system.linux_accounts`.

.. contents::
   :local:
   :depth: 2


.. Entry point title

Entry point ``main`` -- Manage accounts on GNU/Linux systems
------------------------------------------------------------

.. version_added


.. Deprecated


Synopsis
^^^^^^^^

.. Description

- Manage Linux accounts
- Autogenerate password if not provided
- Deploy SSH public keys to users

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
        <div class="ansibleOptionAnchor" id="parameter-main--linux_accounts_list"></div>

      .. _ansible_collections.vfricou.system.linux_accounts_role__parameter-main__linux_accounts_list:

      .. rst-class:: ansible-option-title

      **linux_accounts_list**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--linux_accounts_list" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary` / :ansible-option-required:`required`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Users specifications list


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--linux_accounts_list/comment"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.vfricou.system.linux_accounts_role__parameter-main__linux_accounts_list/comment:

      .. rst-class:: ansible-option-title

      **comment**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--linux_accounts_list/comment" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      User description (GECOS)


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--linux_accounts_list/force_passwd_change"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.vfricou.system.linux_accounts_role__parameter-main__linux_accounts_list/force_passwd_change:

      .. rst-class:: ansible-option-title

      **force_passwd_change**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--linux_accounts_list/force_passwd_change" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Force user password update


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry:`false`
      - :ansible-option-choices-entry:`true`


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--linux_accounts_list/groups"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.vfricou.system.linux_accounts_role__parameter-main__linux_accounts_list/groups:

      .. rst-class:: ansible-option-title

      **groups**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--linux_accounts_list/groups" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=string`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Additionnal user groups


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--linux_accounts_list/home"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.vfricou.system.linux_accounts_role__parameter-main__linux_accounts_list/home:

      .. rst-class:: ansible-option-title

      **home**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--linux_accounts_list/home" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      User home path


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"/home/\<name\>"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--linux_accounts_list/name"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.vfricou.system.linux_accounts_role__parameter-main__linux_accounts_list/name:

      .. rst-class:: ansible-option-title

      **name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--linux_accounts_list/name" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string` / :ansible-option-required:`required`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      User name


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--linux_accounts_list/pass"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.vfricou.system.linux_accounts_role__parameter-main__linux_accounts_list/pass:

      .. rst-class:: ansible-option-title

      **pass**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--linux_accounts_list/pass" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      User password

      :strong:`Must` defined for types :literal:`plain` and :literal:`encrypted`


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--linux_accounts_list/pass_type"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.vfricou.system.linux_accounts_role__parameter-main__linux_accounts_list/pass_type:

      .. rst-class:: ansible-option-title

      **pass_type**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--linux_accounts_list/pass_type" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      User password type


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry:`"plain"`
      - :ansible-option-choices-entry:`"encrypted"`
      - :ansible-option-choices-entry:`"autogen"`
      - :ansible-option-choices-entry:`"passphrase"`
      - :ansible-option-choices-entry:`"locked"`


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--linux_accounts_list/passphrase_params"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.vfricou.system.linux_accounts_role__parameter-main__linux_accounts_list/passphrase_params:

      .. rst-class:: ansible-option-title

      **passphrase_params**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--linux_accounts_list/passphrase_params" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=string`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Passphrase format settings

      :strong:`Order is mandatory`

      :strong:`Order`

      :literal:`min\_length`\ : Minimum word length

      :literal:`max\_length`\ : Maximum word length

      :literal:`numwords`\ : Word count for passphrase

      :literal:`delimiter`\ : Delimiters

      :literal:`case`\ : Case format

      Refer to \ `community.general.random\_string <https://docs.ansible.com/ansible/latest/collections/community/general/random_words_lookup.html#ansible-collections-community-general-random-words-lookup>`__


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`[5, 8, 6, "-", "capitalize"]`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--linux_accounts_list/shell"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.vfricou.system.linux_accounts_role__parameter-main__linux_accounts_list/shell:

      .. rst-class:: ansible-option-title

      **shell**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--linux_accounts_list/shell" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      User login shell


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry-default:`"/usr/bin/bash"` :ansible-option-choices-default-mark:`← (default)`
      - :ansible-option-choices-entry:`"/bin/bash"`
      - :ansible-option-choices-entry:`"/usr/bin/zsh"`
      - :ansible-option-choices-entry:`"/bin/zsh"`
      - :ansible-option-choices-entry:`"/usr/bin/false"`
      - :ansible-option-choices-entry:`"/bin/false"`
      - :ansible-option-choices-entry:`"/usr/sbin/nologin"`
      - :ansible-option-choices-entry:`"/sbin/nologin"`


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--linux_accounts_list/ssh_keys"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.vfricou.system.linux_accounts_role__parameter-main__linux_accounts_list/ssh_keys:

      .. rst-class:: ansible-option-title

      **ssh_keys**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--linux_accounts_list/ssh_keys" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      User SSH public keys to deploy


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--linux_accounts_list/ssh_keys/content"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.vfricou.system.linux_accounts_role__parameter-main__linux_accounts_list/ssh_keys/content:

      .. rst-class:: ansible-option-title

      **content**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--linux_accounts_list/ssh_keys/content" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string` / :ansible-option-required:`required`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      SSH public key


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--linux_accounts_list/ssh_keys/opts"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.vfricou.system.linux_accounts_role__parameter-main__linux_accounts_list/ssh_keys/opts:

      .. rst-class:: ansible-option-title

      **opts**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--linux_accounts_list/ssh_keys/opts" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      SSH public key options


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--linux_accounts_list/ssh_keys/state"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.vfricou.system.linux_accounts_role__parameter-main__linux_accounts_list/ssh_keys/state:

      .. rst-class:: ansible-option-title

      **state**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--linux_accounts_list/ssh_keys/state" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string` / :ansible-option-required:`required`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      SSH public key status


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry:`"present"`
      - :ansible-option-choices-entry:`"absent"`


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--linux_accounts_list/state"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.vfricou.system.linux_accounts_role__parameter-main__linux_accounts_list/state:

      .. rst-class:: ansible-option-title

      **state**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--linux_accounts_list/state" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      User state


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry-default:`"present"` :ansible-option-choices-default-mark:`← (default)`
      - :ansible-option-choices-entry:`"absent"`


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--linux_accounts_list/system"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.vfricou.system.linux_accounts_role__parameter-main__linux_accounts_list/system:

      .. rst-class:: ansible-option-title

      **system**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--linux_accounts_list/system" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Define system account


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry-default:`false` :ansible-option-choices-default-mark:`← (default)`
      - :ansible-option-choices-entry:`true`


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--linux_accounts_no_log"></div>

      .. _ansible_collections.vfricou.system.linux_accounts_role__parameter-main__linux_accounts_no_log:

      .. rst-class:: ansible-option-title

      **linux_accounts_no_log**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--linux_accounts_no_log" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      No log directive


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry:`false`
      - :ansible-option-choices-entry-default:`true` :ansible-option-choices-default-mark:`← (default)`


      .. raw:: html

        </div>


.. Attributes


.. Notes


.. Seealso


Examples
^^^^^^^^

.. code-block:: yaml+jinja

    # Create user with autogen password
    linux_accounts_list:
      - name: ansible
        comment: 'Ansible remote user'
        state: 'present'
        pass_type: 'autogen'

    # Create user with autogen password, add it to group and public ssh authorized keys
    linux_accounts_list:
      - name: ansible
        comment: 'Ansible remote user'
        state: 'present'
        pass_type: 'autogen'
        groups:
          - <group1>
          - <group2>
        ssh_keys:
          - content: '<public_ssh_key_content>'
            state: 'present'

    # Create system user with password lock and add ssh authorized keys
    linux_accounts_list:
      - name: ansible
        comment: 'Ansible remote user'
        state: 'present'
        system: true
        pass_type: 'locked'
        ssh_keys:
          - content: '<public_ssh_key_content>'
            state: 'present'

    # Remove user account (automaticaly delete home directory)
    linux_accounts_list:
      - name: ansible
        state: 'absent'


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
