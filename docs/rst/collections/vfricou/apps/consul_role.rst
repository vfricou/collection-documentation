.. Document meta

:orphan:

.. |antsibull-internal-nbsp| unicode:: 0xA0
    :trim:

.. meta::
  :antsibull-docs: 2.16.3

.. Anchors

.. _ansible_collections.vfricou.apps.consul_role:

.. Title

vfricou.apps.consul role -- Install and configure Hashicorp Consul
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. Collection note

.. note::
    This role is part of the `vfricou.apps collection <https://galaxy.ansible.com/ui/repo/published/vfricou/apps/>`_ (version 1.0.0).

    It is not included in ``ansible-core``.
    To check whether it is installed, run :code:`ansible-galaxy collection list`.

    To install it use: :code:`ansible-galaxy collection install vfricou.apps`.

    To use it in a playbook, specify: :code:`vfricou.apps.consul`.

.. contents::
   :local:
   :depth: 2


.. Entry point title

Entry point ``main`` -- Install and configure Hashicorp Consul
--------------------------------------------------------------

.. version_added


.. Deprecated


Synopsis
^^^^^^^^

.. Description

- Install Hashicorp Consul
- Configure Hashicorp Consul
- Manage Server and Agent mode

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
        <div class="ansibleOptionAnchor" id="parameter-main--consul_base_dir_path"></div>

      .. _ansible_collections.vfricou.apps.consul_role__parameter-main__consul_base_dir_path:

      .. rst-class:: ansible-option-title

      **consul_base_dir_path**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--consul_base_dir_path" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Folder where store consul binaries and datas


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"/opt/consul"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--consul_conf_bind_address"></div>

      .. _ansible_collections.vfricou.apps.consul_role__parameter-main__consul_conf_bind_address:

      .. rst-class:: ansible-option-title

      **consul_conf_bind_address**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--consul_conf_bind_address" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Consul bind address


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"0.0.0.0"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--consul_conf_client_address"></div>

      .. _ansible_collections.vfricou.apps.consul_role__parameter-main__consul_conf_client_address:

      .. rst-class:: ansible-option-title

      **consul_conf_client_address**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--consul_conf_client_address" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Consul client address


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"0.0.0.0"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--consul_conf_datacenter_name"></div>

      .. _ansible_collections.vfricou.apps.consul_role__parameter-main__consul_conf_datacenter_name:

      .. rst-class:: ansible-option-title

      **consul_conf_datacenter_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--consul_conf_datacenter_name" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string` / :ansible-option-required:`required`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Consul datacenter name


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--consul_conf_domain"></div>

      .. _ansible_collections.vfricou.apps.consul_role__parameter-main__consul_conf_domain:

      .. rst-class:: ansible-option-title

      **consul_conf_domain**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--consul_conf_domain" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string` / :ansible-option-required:`required`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Consul DNS domain


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--consul_conf_enable_ui"></div>

      .. _ansible_collections.vfricou.apps.consul_role__parameter-main__consul_conf_enable_ui:

      .. rst-class:: ansible-option-title

      **consul_conf_enable_ui**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--consul_conf_enable_ui" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Enable Consul UI for server


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry:`false`
      - :ansible-option-choices-entry-default:`true` :ansible-option-choices-default-mark:`← (default)`


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--consul_conf_encrypt_key"></div>

      .. _ansible_collections.vfricou.apps.consul_role__parameter-main__consul_conf_encrypt_key:

      .. rst-class:: ansible-option-title

      **consul_conf_encrypt_key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--consul_conf_encrypt_key" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string` / :ansible-option-required:`required`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Consul encryption key


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--consul_conf_log_level"></div>

      .. _ansible_collections.vfricou.apps.consul_role__parameter-main__consul_conf_log_level:

      .. rst-class:: ansible-option-title

      **consul_conf_log_level**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--consul_conf_log_level" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Consul logging level


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"INFO"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--consul_download_url"></div>

      .. _ansible_collections.vfricou.apps.consul_role__parameter-main__consul_download_url:

      .. rst-class:: ansible-option-title

      **consul_download_url**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--consul_download_url" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Hashicorp Consul download URL base path

      Override default URL to specific use URL

      By default computed to form {{ consul\_download\_url\_base }}/{{ consul\_version }}/consul\_{{ consul\_version }}\_linux\_{{ ansible\_architecture }}


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--consul_group"></div>

      .. _ansible_collections.vfricou.apps.consul_role__parameter-main__consul_group:

      .. rst-class:: ansible-option-title

      **consul_group**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--consul_group" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      System group will run Consul


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"consul"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--consul_port_dns"></div>

      .. _ansible_collections.vfricou.apps.consul_role__parameter-main__consul_port_dns:

      .. rst-class:: ansible-option-title

      **consul_port_dns**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--consul_port_dns" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Consul DNS port.

      Consult https://developer.hashicorp.com/consul/docs/install/ports


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`8600`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--consul_port_grpc"></div>

      .. _ansible_collections.vfricou.apps.consul_role__parameter-main__consul_port_grpc:

      .. rst-class:: ansible-option-title

      **consul_port_grpc**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--consul_port_grpc" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Consul gRPC port

      Consult https://developer.hashicorp.com/consul/docs/install/ports


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--consul_port_grpc_tls"></div>

      .. _ansible_collections.vfricou.apps.consul_role__parameter-main__consul_port_grpc_tls:

      .. rst-class:: ansible-option-title

      **consul_port_grpc_tls**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--consul_port_grpc_tls" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Consul gRPC TLS port

      Consult https://developer.hashicorp.com/consul/docs/install/ports


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`8503`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--consul_port_http"></div>

      .. _ansible_collections.vfricou.apps.consul_role__parameter-main__consul_port_http:

      .. rst-class:: ansible-option-title

      **consul_port_http**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--consul_port_http" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Consul HTTP port.

      Consult https://developer.hashicorp.com/consul/docs/install/ports


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`8500`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--consul_port_https"></div>

      .. _ansible_collections.vfricou.apps.consul_role__parameter-main__consul_port_https:

      .. rst-class:: ansible-option-title

      **consul_port_https**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--consul_port_https" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Consul HTTPS port.

      Consult https://developer.hashicorp.com/consul/docs/install/ports


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--consul_port_serf_lan"></div>

      .. _ansible_collections.vfricou.apps.consul_role__parameter-main__consul_port_serf_lan:

      .. rst-class:: ansible-option-title

      **consul_port_serf_lan**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--consul_port_serf_lan" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Consul SERF LAN port

      Consult https://developer.hashicorp.com/consul/docs/install/ports


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`8301`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--consul_port_serf_wan"></div>

      .. _ansible_collections.vfricou.apps.consul_role__parameter-main__consul_port_serf_wan:

      .. rst-class:: ansible-option-title

      **consul_port_serf_wan**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--consul_port_serf_wan" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Consul SERF WAN port

      Consult https://developer.hashicorp.com/consul/docs/install/ports


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--consul_port_server"></div>

      .. _ansible_collections.vfricou.apps.consul_role__parameter-main__consul_port_server:

      .. rst-class:: ansible-option-title

      **consul_port_server**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--consul_port_server" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Consul Server port

      Consult https://developer.hashicorp.com/consul/docs/install/ports


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`8300`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--consul_services"></div>

      .. _ansible_collections.vfricou.apps.consul_role__parameter-main__consul_services:

      .. rst-class:: ansible-option-title

      **consul_services**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--consul_services" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Services to declare


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--consul_username"></div>

      .. _ansible_collections.vfricou.apps.consul_role__parameter-main__consul_username:

      .. rst-class:: ansible-option-title

      **consul_username**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--consul_username" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      System user will run Consul


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"consul"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--consul_version"></div>

      .. _ansible_collections.vfricou.apps.consul_role__parameter-main__consul_version:

      .. rst-class:: ansible-option-title

      **consul_version**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--consul_version" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Hashicorp Consul version


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"1.20.1"`

      .. raw:: html

        </div>


.. Attributes


.. Notes


.. Seealso


Examples
^^^^^^^^

.. code-block:: yaml+jinja

    # Playbook Consul cluster deployment
    - name: 'Consul Cluster'
      hosts:
        - consul_cluster
      gather_facts: true
      roles:
        - role: vfricou.apps.consul
          vars:
            consul_conf_domain: "consul"
            consul_conf_datacenter_name: "dc"
            consul_conf_encrypt_key: "<secret_encryption_key>"

    # Plakbook Consul agent deployment
    - name: 'Consul Cluster'
      hosts:
        - consul_agents
      gather_facts: true
      roles:
        - role: vfricou.apps.consul
          vars:
            consul_conf_domain: "consul"
            consul_conf_datacenter_name: "dc"
            consul_conf_encrypt_key: "<secret_encryption_key>"

    # Playbook Consul agent deployment with service - Example for Vault
    - name: 'Consul Cluster'
      hosts:
        - consul_agents
      gather_facts: true
      roles:
        - role: vfricou.apps.consul
          vars:
            consul_conf_domain: "consul"
            consul_conf_datacenter_name: "dc"
            consul_conf_encrypt_key: "<secret_encryption_key>"
            consul_services: |
              services {
                id = "vault"
                name = "vault"
                port = 8200
                tags = [
                  "vault"
                ]
                check = {
                    id = "vault"
                    name = "Check Vault API liveness"
                    http = "https://127.0.0.1:8200"
                    tls_skip_verify = true
                    interval = "60s"
                }
              }


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
