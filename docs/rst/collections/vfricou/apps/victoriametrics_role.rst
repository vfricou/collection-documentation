.. Document meta

:orphan:

.. |antsibull-internal-nbsp| unicode:: 0xA0
    :trim:

.. meta::
  :antsibull-docs: 2.16.3

.. Anchors

.. _ansible_collections.vfricou.apps.victoriametrics_role:

.. Title

vfricou.apps.victoriametrics role -- Install and configure Victoria Metrics
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. Collection note

.. note::
    This role is part of the `vfricou.apps collection <https://galaxy.ansible.com/ui/repo/published/vfricou/apps/>`_ (version 1.0.0).

    It is not included in ``ansible-core``.
    To check whether it is installed, run :code:`ansible-galaxy collection list`.

    To install it use: :code:`ansible-galaxy collection install vfricou.apps`.

    To use it in a playbook, specify: :code:`vfricou.apps.victoriametrics`.

.. contents::
   :local:
   :depth: 2


.. Entry point title

Entry point ``main`` -- Install and configure Victoria Metrics
--------------------------------------------------------------

.. version_added


.. Deprecated


Synopsis
^^^^^^^^

.. Description

- Install Victoria Metrics

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
        <div class="ansibleOptionAnchor" id="parameter-main--victoriametrics_base_path"></div>

      .. _ansible_collections.vfricou.apps.victoriametrics_role__parameter-main__victoriametrics_base_path:

      .. rst-class:: ansible-option-title

      **victoriametrics_base_path**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--victoriametrics_base_path" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Base path containing VictoriaMetrics binaries, datas, …


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"/opt/victoriametrics"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--victoriametrics_data_path"></div>

      .. _ansible_collections.vfricou.apps.victoriametrics_role__parameter-main__victoriametrics_data_path:

      .. rst-class:: ansible-option-title

      **victoriametrics_data_path**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--victoriametrics_data_path" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      VictoriaMetrics data path override if different than default path


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--victoriametrics_dl_url"></div>

      .. _ansible_collections.vfricou.apps.victoriametrics_role__parameter-main__victoriametrics_dl_url:

      .. rst-class:: ansible-option-title

      **victoriametrics_dl_url**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--victoriametrics_dl_url" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Define override download URL for VictoriaMetrics package (without package name)


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--victoriametrics_extra_configs"></div>

      .. _ansible_collections.vfricou.apps.victoriametrics_role__parameter-main__victoriametrics_extra_configs:

      .. rst-class:: ansible-option-title

      **victoriametrics_extra_configs**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--victoriametrics_extra_configs" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Define additionnal VictoriaMetrics options


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`[]`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--victoriametrics_group"></div>

      .. _ansible_collections.vfricou.apps.victoriametrics_role__parameter-main__victoriametrics_group:

      .. rst-class:: ansible-option-title

      **victoriametrics_group**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--victoriametrics_group" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      VictoriaMetrics system group


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"victoriametrics"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--victoriametrics_max_concurrent_insert"></div>

      .. _ansible_collections.vfricou.apps.victoriametrics_role__parameter-main__victoriametrics_max_concurrent_insert:

      .. rst-class:: ansible-option-title

      **victoriametrics_max_concurrent_insert**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--victoriametrics_max_concurrent_insert" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      The maximum number of concurrent insert requests.

      Set higher value when clients send data over slow networks.


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`32`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--victoriametrics_pkg_name"></div>

      .. _ansible_collections.vfricou.apps.victoriametrics_role__parameter-main__victoriametrics_pkg_name:

      .. rst-class:: ansible-option-title

      **victoriametrics_pkg_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--victoriametrics_pkg_name" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Define override package name to download and extract for VictoriaMetrics


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--victoriametrics_retention_period"></div>

      .. _ansible_collections.vfricou.apps.victoriametrics_role__parameter-main__victoriametrics_retention_period:

      .. rst-class:: ansible-option-title

      **victoriametrics_retention_period**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--victoriametrics_retention_period" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Data retention period in days


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"14"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--victoriametrics_scrape_interval"></div>

      .. _ansible_collections.vfricou.apps.victoriametrics_role__parameter-main__victoriametrics_scrape_interval:

      .. rst-class:: ansible-option-title

      **victoriametrics_scrape_interval**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--victoriametrics_scrape_interval" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Interval for self-scraping own metrics at /metrics page


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"30s"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--victoriametrics_search_max_unique_ts"></div>

      .. _ansible_collections.vfricou.apps.victoriametrics_role__parameter-main__victoriametrics_search_max_unique_ts:

      .. rst-class:: ansible-option-title

      **victoriametrics_search_max_unique_ts**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--victoriametrics_search_max_unique_ts" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      The maximum number of unique time series.

      This option allows limiting memory usage.


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`900000`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--victoriametrics_type"></div>

      .. _ansible_collections.vfricou.apps.victoriametrics_role__parameter-main__victoriametrics_type:

      .. rst-class:: ansible-option-title

      **victoriametrics_type**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--victoriametrics_type" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Victoriametrics deployment type


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry-default:`"single"` :ansible-option-choices-default-mark:`← (default)`


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--victoriametrics_user"></div>

      .. _ansible_collections.vfricou.apps.victoriametrics_role__parameter-main__victoriametrics_user:

      .. rst-class:: ansible-option-title

      **victoriametrics_user**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--victoriametrics_user" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      VictoriaMetrics system user


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"victoriametrics"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--victoriametrics_version"></div>

      .. _ansible_collections.vfricou.apps.victoriametrics_role__parameter-main__victoriametrics_version:

      .. rst-class:: ansible-option-title

      **victoriametrics_version**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--victoriametrics_version" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      VictoriaMetrics version to install

      Refer to \ `GitHub Releases <https://github.com/VictoriaMetrics/VictoriaMetrics/releases/tag/v1.125.0>`__


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"v1.125.0"`

      .. raw:: html

        </div>


.. Attributes


.. Notes


.. Seealso


Examples
^^^^^^^^

.. code-block:: yaml+jinja

    # Playbook VictoriaMetrics deployment
    ---
    - name: 'VictoriaMetrics'
      hosts:
        - vmetric_server
      vars:
        victoriametrics_type: single
      roles:
        - name: 'Install VictoriaMetrics single'
          role: vfricou.apps.victoriametrics'


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
