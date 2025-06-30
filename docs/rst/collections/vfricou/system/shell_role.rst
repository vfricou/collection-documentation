.. Document meta

:orphan:

.. |antsibull-internal-nbsp| unicode:: 0xA0
    :trim:

.. meta::
  :antsibull-docs: 2.16.3

.. Anchors

.. _ansible_collections.vfricou.system.shell_role:

.. Title

vfricou.system.shell role -- Shell configuration
++++++++++++++++++++++++++++++++++++++++++++++++

.. Collection note

.. note::
    This role is part of the `vfricou.system collection <https://galaxy.ansible.com/ui/repo/published/vfricou/system/>`_ (version 1.0.0).

    It is not included in ``ansible-core``.
    To check whether it is installed, run :code:`ansible-galaxy collection list`.

    To install it use: :code:`ansible-galaxy collection install vfricou.system`.

    To use it in a playbook, specify: :code:`vfricou.system.shell`.

.. contents::
   :local:
   :depth: 2


.. Entry point title

Entry point ``main`` -- Shell configuration
-------------------------------------------

.. version_added


.. Deprecated


Synopsis
^^^^^^^^

.. Description

- Configure GNU/Linux shells

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
        <div class="ansibleOptionAnchor" id="parameter-main--shell_asdf_access_group"></div>

      .. _ansible_collections.vfricou.system.shell_role__parameter-main__shell_asdf_access_group:

      .. rst-class:: ansible-option-title

      **shell_asdf_access_group**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--shell_asdf_access_group" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      ASDF system group to allow binary usage


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"asdfusers"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--shell_asdf_dl_url"></div>

      .. _ansible_collections.vfricou.system.shell_role__parameter-main__shell_asdf_dl_url:

      .. rst-class:: ansible-option-title

      **shell_asdf_dl_url**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--shell_asdf_dl_url" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      ASDF base URL to download package


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"https://github.com/asdf-vm/asdf/releases/download/{{ shell\_asdf\_version }}"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--shell_asdf_force_update"></div>

      .. _ansible_collections.vfricou.system.shell_role__parameter-main__shell_asdf_force_update:

      .. rst-class:: ansible-option-title

      **shell_asdf_force_update**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--shell_asdf_force_update" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Force ASDF update to specified version


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry-default:`false` :ansible-option-choices-default-mark:`← (default)`
      - :ansible-option-choices-entry:`true`


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--shell_asdf_install"></div>

      .. _ansible_collections.vfricou.system.shell_role__parameter-main__shell_asdf_install:

      .. rst-class:: ansible-option-title

      **shell_asdf_install**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--shell_asdf_install" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Activate ASDF tool installation


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry-default:`false` :ansible-option-choices-default-mark:`← (default)`
      - :ansible-option-choices-entry:`true`


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--shell_asdf_pkg_name"></div>

      .. _ansible_collections.vfricou.system.shell_role__parameter-main__shell_asdf_pkg_name:

      .. rst-class:: ansible-option-title

      **shell_asdf_pkg_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--shell_asdf_pkg_name" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      ASDF package name


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"asdf-{{ shell\_asdf\_version }}-linux-amd64.tar.gz"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--shell_asdf_version"></div>

      .. _ansible_collections.vfricou.system.shell_role__parameter-main__shell_asdf_version:

      .. rst-class:: ansible-option-title

      **shell_asdf_version**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--shell_asdf_version" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Define ASDF version to install


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"v0.18.0"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--shell_bash_prompt_colors_enabled"></div>

      .. _ansible_collections.vfricou.system.shell_role__parameter-main__shell_bash_prompt_colors_enabled:

      .. rst-class:: ansible-option-title

      **shell_bash_prompt_colors_enabled**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--shell_bash_prompt_colors_enabled" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Enable colored bash prompt


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry:`false`
      - :ansible-option-choices-entry-default:`true` :ansible-option-choices-default-mark:`← (default)`


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--shell_bash_prompt_host_color"></div>

      .. _ansible_collections.vfricou.system.shell_role__parameter-main__shell_bash_prompt_host_color:

      .. rst-class:: ansible-option-title

      **shell_bash_prompt_host_color**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--shell_bash_prompt_host_color" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Define host prompt part color


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry:`"dark\_gray"`
      - :ansible-option-choices-entry:`"black"`
      - :ansible-option-choices-entry:`"light\_red"`
      - :ansible-option-choices-entry:`"red"`
      - :ansible-option-choices-entry:`"light\_green"`
      - :ansible-option-choices-entry:`"green"`
      - :ansible-option-choices-entry:`"yellow"`
      - :ansible-option-choices-entry:`"brown"`
      - :ansible-option-choices-entry-default:`"light\_blue"` :ansible-option-choices-default-mark:`← (default)`
      - :ansible-option-choices-entry:`"blue"`
      - :ansible-option-choices-entry:`"light\_purple"`
      - :ansible-option-choices-entry:`"purple"`
      - :ansible-option-choices-entry:`"light\_cyan"`
      - :ansible-option-choices-entry:`"cyan"`
      - :ansible-option-choices-entry:`"white"`
      - :ansible-option-choices-entry:`"light\_gray"`


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--shell_config_users"></div>

      .. _ansible_collections.vfricou.system.shell_role__parameter-main__shell_config_users:

      .. rst-class:: ansible-option-title

      **shell_config_users**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--shell_config_users" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Define user list where to update shell rc installed


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`["root"]`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--shell_direnv_access_group"></div>

      .. _ansible_collections.vfricou.system.shell_role__parameter-main__shell_direnv_access_group:

      .. rst-class:: ansible-option-title

      **shell_direnv_access_group**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--shell_direnv_access_group" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Direnv system group to allow binary usage


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"direnvusers"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--shell_direnv_dl_url"></div>

      .. _ansible_collections.vfricou.system.shell_role__parameter-main__shell_direnv_dl_url:

      .. rst-class:: ansible-option-title

      **shell_direnv_dl_url**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--shell_direnv_dl_url" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Base URL to download Direnv package


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"https://github.com/direnv/direnv/releases/download/{{ shell\_direnv\_version }}"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--shell_direnv_force_update"></div>

      .. _ansible_collections.vfricou.system.shell_role__parameter-main__shell_direnv_force_update:

      .. rst-class:: ansible-option-title

      **shell_direnv_force_update**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--shell_direnv_force_update" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Force Direnv update to specified version


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry-default:`false` :ansible-option-choices-default-mark:`← (default)`
      - :ansible-option-choices-entry:`true`


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--shell_direnv_install"></div>

      .. _ansible_collections.vfricou.system.shell_role__parameter-main__shell_direnv_install:

      .. rst-class:: ansible-option-title

      **shell_direnv_install**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--shell_direnv_install" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Activate Direnv tool installation


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry-default:`false` :ansible-option-choices-default-mark:`← (default)`
      - :ansible-option-choices-entry:`true`


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--shell_direnv_pkg_name"></div>

      .. _ansible_collections.vfricou.system.shell_role__parameter-main__shell_direnv_pkg_name:

      .. rst-class:: ansible-option-title

      **shell_direnv_pkg_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--shell_direnv_pkg_name" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Direnv package name


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"direnv.linux-amd64"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--shell_direnv_version"></div>

      .. _ansible_collections.vfricou.system.shell_role__parameter-main__shell_direnv_version:

      .. rst-class:: ansible-option-title

      **shell_direnv_version**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--shell_direnv_version" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Direnv version to install


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"v2.36.0"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--shell_to_configure"></div>

      .. _ansible_collections.vfricou.system.shell_role__parameter-main__shell_to_configure:

      .. rst-class:: ansible-option-title

      **shell_to_configure**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--shell_to_configure" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Define shell to configure


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry-default:`"bash"` :ansible-option-choices-default-mark:`← (default)`
      - :ansible-option-choices-entry:`"zsh"`


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--shell_zsh_install"></div>

      .. _ansible_collections.vfricou.system.shell_role__parameter-main__shell_zsh_install:

      .. rst-class:: ansible-option-title

      **shell_zsh_install**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--shell_zsh_install" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Install ZSH shell


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry-default:`false` :ansible-option-choices-default-mark:`← (default)`
      - :ansible-option-choices-entry:`true`


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--shell_zsh_omz_install"></div>

      .. _ansible_collections.vfricou.system.shell_role__parameter-main__shell_zsh_omz_install:

      .. rst-class:: ansible-option-title

      **shell_zsh_omz_install**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--shell_zsh_omz_install" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Install Oh-My-Zsh


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry:`false`
      - :ansible-option-choices-entry-default:`true` :ansible-option-choices-default-mark:`← (default)`


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--shell_zsh_omz_plugins"></div>

      .. _ansible_collections.vfricou.system.shell_role__parameter-main__shell_zsh_omz_plugins:

      .. rst-class:: ansible-option-title

      **shell_zsh_omz_plugins**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--shell_zsh_omz_plugins" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Oh-My-Zsh plugins to activate

      Limited choices of plugins for this role

      Refer to \ `https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins <https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins>`__ for plugins details


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry:`"asdf"`
      - :ansible-option-choices-entry-default:`"colored-man-pages"` :ansible-option-choices-default-mark:`← (default)`
      - :ansible-option-choices-entry:`"direnv"`
      - :ansible-option-choices-entry:`"eza"`
      - :ansible-option-choices-entry-default:`"git"` :ansible-option-choices-default-mark:`← (default)`
      - :ansible-option-choices-entry:`"history"`
      - :ansible-option-choices-entry:`"k9s"`
      - :ansible-option-choices-entry:`"mercurial"`
      - :ansible-option-choices-entry-default:`"zsh-interactive-cd"` :ansible-option-choices-default-mark:`← (default)`


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`["git", "colored-man-pages", "zsh-interactive-cd"]`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--shell_zsh_omz_repo"></div>

      .. _ansible_collections.vfricou.system.shell_role__parameter-main__shell_zsh_omz_repo:

      .. rst-class:: ansible-option-title

      **shell_zsh_omz_repo**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--shell_zsh_omz_repo" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Oh-My-Zsh repository


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"https://github.com/ohmyzsh/ohmyzsh.git"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--shell_zsh_omz_theme"></div>

      .. _ansible_collections.vfricou.system.shell_role__parameter-main__shell_zsh_omz_theme:

      .. rst-class:: ansible-option-title

      **shell_zsh_omz_theme**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--shell_zsh_omz_theme" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Oh-My-Zsh theme


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry:`"robbyrussell"`
      - :ansible-option-choices-entry-default:`"agnoster"` :ansible-option-choices-default-mark:`← (default)`


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--shell_zsh_omz_update"></div>

      .. _ansible_collections.vfricou.system.shell_role__parameter-main__shell_zsh_omz_update:

      .. rst-class:: ansible-option-title

      **shell_zsh_omz_update**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--shell_zsh_omz_update" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Activate Oh-My-Zsh auto-update

      :literal:`disabled` : Manually update Oh-My-Zsh

      :literal:`auto` : Automatically update Oh-My-Zsh

      :literal:`reminder` : Just remind to update Oh-My-Zsh


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry:`"disabled"`
      - :ansible-option-choices-entry:`"auto"`
      - :ansible-option-choices-entry-default:`"reminder"` :ansible-option-choices-default-mark:`← (default)`


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--shell_zsh_omz_update_frequency"></div>

      .. _ansible_collections.vfricou.system.shell_role__parameter-main__shell_zsh_omz_update_frequency:

      .. rst-class:: ansible-option-title

      **shell_zsh_omz_update_frequency**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--shell_zsh_omz_update_frequency" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Oh-My-Zsh update frequency in days


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`13`

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
