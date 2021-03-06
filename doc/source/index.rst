..
      Copyright 2017 AT&T Intellectual Property.
      All Rights Reserved.

      Licensed under the Apache License, Version 2.0 (the "License"); you may
      not use this file except in compliance with the License. You may obtain
      a copy of the License at

          http://www.apache.org/licenses/LICENSE-2.0

      Unless required by applicable law or agreed to in writing, software
      distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
      WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
      License for the specific language governing permissions and limitations
      under the License.

====================================
Welcome to Shipyard's documentation!
====================================

Shipyard is a directed acyclic graph controller for Kubernetes and OpenStack
control plane life-cycle management, and is part of the `Airship`_ platform.

.. toctree::
   :maxdepth: 2

   sampleconf
   API
   action-commands
   CLI
   site-definition-documents
   client-user-guide
   deployment-guide
   policy-enforcement

Building this Documentation
---------------------------

Use ``make docs`` or ``tox -e docs`` to generate these docs. This will and
build an html version of this documentation that can be viewed using a browser
at doc/build/index.html on the local filesystem.

.. _Airship: https://airshipit.org
