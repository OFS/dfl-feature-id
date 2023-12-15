.. SPDX-License-Identifier: GPL-2.0

========================================
Device Feature List (DFL) Parameter Ids
========================================

Parameter IDs within a version 1 feature are often private to a particular
feature GUID. The first feature in an AFU at the AFU's MMIO offset 0 has a
unique problem: the GUID of the feature is the AFU's GUID. When an AFU feature
parameter must be interpreted by the system, globally defined parameter IDs
are needed. The following parameter IDs are valid for any AFU feature and
should not be used for other meanings within an AFU:

.. list-table:: AFU First Feature Parameter IDs
   :widths: 2 2 2
   :header-rows: 1

   * - Parameter Name
     - ID
     - Version

   * - MSI-X
     - 1
     - 0

   * - Child AFU GUID list
     - 2
     - 0

   * - Reserved
     - 3 - 0xff
     -
