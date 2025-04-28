.. Document meta

:orphan:

.. |antsibull-internal-nbsp| unicode:: 0xA0
    :trim:

.. meta::
  :antsibull-docs: 2.16.3

.. Anchors

.. _ansible_collections.vfricou.apps.nginx_role:

.. Title

vfricou.apps.nginx role -- Install and configure Nginx
++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. Collection note

.. note::
    This role is part of the `vfricou.apps collection <https://galaxy.ansible.com/ui/repo/published/vfricou/apps/>`_ (version 1.0.0).

    It is not included in ``ansible-core``.
    To check whether it is installed, run :code:`ansible-galaxy collection list`.

    To install it use: :code:`ansible-galaxy collection install vfricou.apps`.

    To use it in a playbook, specify: :code:`vfricou.apps.nginx`.

.. contents::
   :local:
   :depth: 2


.. Entry point title

Entry point ``main`` -- Install and configure Nginx
---------------------------------------------------

.. version_added


.. Deprecated


Synopsis
^^^^^^^^

.. Description

- Install Nginx
- Manage Nginx general configuration
- Manage Nginx vhosts configuration
- Manage Nginx logrotate configuration

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
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_conf_dh_size"></div>

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_conf_dh_size:

      .. rst-class:: ansible-option-title

      **nginx_conf_dh_size**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_conf_dh_size" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Diffie Hellman size in bits


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`2048`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_conf_gzip_compression"></div>

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_conf_gzip_compression:

      .. rst-class:: ansible-option-title

      **nginx_conf_gzip_compression**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_conf_gzip_compression" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Enable :literal:`gzip` directive in Nginx general configuration


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry-default:`false` :ansible-option-choices-default-mark:`← (default)`
      - :ansible-option-choices-entry:`true`


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_conf_keepalive_timeout"></div>

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_conf_keepalive_timeout:

      .. rst-class:: ansible-option-title

      **nginx_conf_keepalive_timeout**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_conf_keepalive_timeout" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Configure :literal:`keepalive\_timeout` directive in Nginx general configuration


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`65`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_conf_sendfile"></div>

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_conf_sendfile:

      .. rst-class:: ansible-option-title

      **nginx_conf_sendfile**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_conf_sendfile" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Enable :literal:`sendfile` directive in Nginx general configuration


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry:`false`
      - :ansible-option-choices-entry-default:`true` :ansible-option-choices-default-mark:`← (default)`


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_conf_tcp_nopush"></div>

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_conf_tcp_nopush:

      .. rst-class:: ansible-option-title

      **nginx_conf_tcp_nopush**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_conf_tcp_nopush" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Enable :literal:`tcp\_nopush` directive in Nginx general configuration


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry-default:`false` :ansible-option-choices-default-mark:`← (default)`
      - :ansible-option-choices-entry:`true`


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_log_path"></div>

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_log_path:

      .. rst-class:: ansible-option-title

      **nginx_log_path**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_log_path" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Nginx logs location base path


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"/var/log/nginx"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_logrotate_general_retention"></div>

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_logrotate_general_retention:

      .. rst-class:: ansible-option-title

      **nginx_logrotate_general_retention**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_logrotate_general_retention" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Logrotation for general nginx logs


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`90`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_logrotate_vhost_retention"></div>

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_logrotate_vhost_retention:

      .. rst-class:: ansible-option-title

      **nginx_logrotate_vhost_retention**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_logrotate_vhost_retention" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Logrotate for vhosts


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`90`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_vhosts"></div>

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_vhosts:

      .. rst-class:: ansible-option-title

      **nginx_vhosts**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_vhosts" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary` / :ansible-option-required:`required`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Nginx vhosts configurations


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_vhosts/custom"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_vhosts/custom:

      .. rst-class:: ansible-option-title

      **custom**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_vhosts/custom" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string` / :ansible-option-required:`required`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Nginx vhost custom configurations

      Use this to declare you location blocks


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_vhosts/include"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_vhosts/include:

      .. rst-class:: ansible-option-title

      **include**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_vhosts/include" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Configuration inclusion declarations


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_vhosts/include/letsencrypt"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_vhosts/include/letsencrypt:

      .. rst-class:: ansible-option-title

      **letsencrypt**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_vhosts/include/letsencrypt" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Enable ACME location block to allow ACME challenges verifications


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry:`false`
      - :ansible-option-choices-entry:`true`


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_vhosts/include/redirect_https"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_vhosts/include/redirect_https:

      .. rst-class:: ansible-option-title

      **redirect_https**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_vhosts/include/redirect_https" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Enable HTTS redirection


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry:`false`
      - :ansible-option-choices-entry:`true`


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_vhosts/include/robots"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_vhosts/include/robots:

      .. rst-class:: ansible-option-title

      **robots**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_vhosts/include/robots" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Enable global robots.txt files (refuse all robots)


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry:`false`
      - :ansible-option-choices-entry:`true`


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_vhosts/logs"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_vhosts/logs:

      .. rst-class:: ansible-option-title

      **logs**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_vhosts/logs" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      vhost logs path


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"C(\<nginx\_log\_path\>)/vhosts/C(vhost.name)"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_vhosts/name"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_vhosts/name:

      .. rst-class:: ansible-option-title

      **name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_vhosts/name" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string` / :ansible-option-required:`required`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      vhost configuration filename


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_vhosts/ports"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_vhosts/ports:

      .. rst-class:: ansible-option-title

      **ports**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_vhosts/ports" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary` / :ansible-option-required:`required`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Ports configuration


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_vhosts/ports/http2"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_vhosts/ports/http2:

      .. rst-class:: ansible-option-title

      **http2**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_vhosts/ports/http2" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Enable http2 directive for SSL vhosts


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry:`false`
      - :ansible-option-choices-entry:`true`


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_vhosts/ports/opts"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_vhosts/ports/opts:

      .. rst-class:: ansible-option-title

      **opts**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_vhosts/ports/opts" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=string`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      HTTPS listen directive options


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_vhosts/ports/port"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_vhosts/ports/port:

      .. rst-class:: ansible-option-title

      **port**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_vhosts/ports/port" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer` / :ansible-option-required:`required`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Port to bind


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_vhosts/ports/type"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_vhosts/ports/type:

      .. rst-class:: ansible-option-title

      **type**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_vhosts/ports/type" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string` / :ansible-option-required:`required`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Port type


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry:`"http"`
      - :ansible-option-choices-entry:`"https"`


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_vhosts/server_names"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_vhosts/server_names:

      .. rst-class:: ansible-option-title

      **server_names**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_vhosts/server_names" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=string` / :ansible-option-required:`required`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Server names


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_vhosts/ssl_opts"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_vhosts/ssl_opts:

      .. rst-class:: ansible-option-title

      **ssl_opts**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_vhosts/ssl_opts" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      vhost configuration options


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_vhosts/ssl_opts/cert_path"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_vhosts/ssl_opts/cert_path:

      .. rst-class:: ansible-option-title

      **cert_path**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_vhosts/ssl_opts/cert_path" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string` / :ansible-option-required:`required`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Path to vhost certificate fullchain


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_vhosts/ssl_opts/chain_path"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_vhosts/ssl_opts/chain_path:

      .. rst-class:: ansible-option-title

      **chain_path**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_vhosts/ssl_opts/chain_path" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string` / :ansible-option-required:`required`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Path to trusted CA chain


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_vhosts/ssl_opts/ciphers"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_vhosts/ssl_opts/ciphers:

      .. rst-class:: ansible-option-title

      **ciphers**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_vhosts/ssl_opts/ciphers" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=string`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Ciphers to use on vhost


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`["ECDHE-ECDSA-AES256-GCM-SHA384", "ECDHE-ECDSA-CHACHA20-POLY1305", "ECDHE-ECDSA-CHACHA20-POLY1305-D", "ECDHE-RSA-AES256-GCM-SHA384", "ECDHE-RSA-CHACHA20-POLY1305", "ECDHE-RSA-CHACHA20-POLY1305-D", "ECDHE-ECDSA-AES128-GCM-SHA256", "ECDHE-RSA-AES128-GCM-SHA256", "!aNULL", "!eNULL", "!EXPORT", "!DES", "!MD5", "!PSK", "!RC4"]`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_vhosts/ssl_opts/ecdh_curve"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_vhosts/ssl_opts/ecdh_curve:

      .. rst-class:: ansible-option-title

      **ecdh_curve**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_vhosts/ssl_opts/ecdh_curve" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=string`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      ECDH curves to use


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`["secp521r1", "secp384r1"]`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_vhosts/ssl_opts/enabled"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_vhosts/ssl_opts/enabled:

      .. rst-class:: ansible-option-title

      **enabled**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_vhosts/ssl_opts/enabled" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean` / :ansible-option-required:`required`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Enable SSL configurations on vhost


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry:`false`
      - :ansible-option-choices-entry:`true`


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_vhosts/ssl_opts/hsts"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_vhosts/ssl_opts/hsts:

      .. rst-class:: ansible-option-title

      **hsts**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_vhosts/ssl_opts/hsts" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Enable HSTS headers


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry:`false`
      - :ansible-option-choices-entry-default:`true` :ansible-option-choices-default-mark:`← (default)`


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_vhosts/ssl_opts/hsts_conf"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_vhosts/ssl_opts/hsts_conf:

      .. rst-class:: ansible-option-title

      **hsts_conf**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_vhosts/ssl_opts/hsts_conf" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      HSTS configurations options


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"max-age=157680000;includeSubDomains"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_vhosts/ssl_opts/key_path"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_vhosts/ssl_opts/key_path:

      .. rst-class:: ansible-option-title

      **key_path**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_vhosts/ssl_opts/key_path" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string` / :ansible-option-required:`required`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Path to vhost private key


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_vhosts/ssl_opts/protocols"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_vhosts/ssl_opts/protocols:

      .. rst-class:: ansible-option-title

      **protocols**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_vhosts/ssl_opts/protocols" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=string`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Protocols to use with SSL enabled


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`["TLSv1.2", "TLSv1.3"]`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_vhosts/ssl_opts/session_buffer_size"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_vhosts/ssl_opts/session_buffer_size:

      .. rst-class:: ansible-option-title

      **session_buffer_size**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_vhosts/ssl_opts/session_buffer_size" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Session buffer


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"1400"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_vhosts/ssl_opts/session_cache_time"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_vhosts/ssl_opts/session_cache_time:

      .. rst-class:: ansible-option-title

      **session_cache_time**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_vhosts/ssl_opts/session_cache_time" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Session cache validity


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"10m"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_vhosts/ssl_opts/session_cache_timeout"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_vhosts/ssl_opts/session_cache_timeout:

      .. rst-class:: ansible-option-title

      **session_cache_timeout**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_vhosts/ssl_opts/session_cache_timeout" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Session cache timeout


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"8h"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_vhosts/ssl_opts/session_ticket"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_vhosts/ssl_opts/session_ticket:

      .. rst-class:: ansible-option-title

      **session_ticket**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_vhosts/ssl_opts/session_ticket" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Activate session tickets


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry:`"on"`
      - :ansible-option-choices-entry-default:`"off"` :ansible-option-choices-default-mark:`← (default)`


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_web_root"></div>

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_web_root:

      .. rst-class:: ansible-option-title

      **nginx_web_root**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_web_root" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Nginx web root location

      Used for ACME challenges


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"/srv/nginx"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--nginx_worker_connnections"></div>

      .. _ansible_collections.vfricou.apps.nginx_role__parameter-main__nginx_worker_connnections:

      .. rst-class:: ansible-option-title

      **nginx_worker_connnections**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--nginx_worker_connnections" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Workers max connections


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`1024`

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
