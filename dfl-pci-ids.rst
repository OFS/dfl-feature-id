.. SPDX-License-Identifier: GPL-2.0

========================================
PCI IDs Containing Device Feature Lists
========================================

This page tracks PCI ID information related to the use of
Device Feature Lists (DFL).


.. list-table:: PCI VID/PIDs accepted into kernel.org for the dfl-pci driver
   :widths: 2 2 2
   :header-rows: 1

   * - Macro
     - Vendor ID
     - Product ID

   * - PCIE_DEVICE_ID_PF_INT_5_X
     - PCI_VENDOR_ID_INTEL 0x8086
     - 0xbcbd

   * - PCIE_DEVICE_ID_VF_INT_5_X
     - PCI_VENDOR_ID_INTEL 0x8086
     - 0xbcbF

   * - PCIE_DEVICE_ID_PF_INT_6_X
     - PCI_VENDOR_ID_INTEL 0x8086
     - 0xbcc0

   * - PCIE_DEVICE_ID_VF_INT_6_X
     - PCI_VENDOR_ID_INTEL 0x8086
     - 0xbcc1

   * - PCIE_DEVICE_ID_PF_DCS_1_X
     - PCI_VENDOR_ID_INTEL 0x8086
     - 0x09c4

   * - PCIE_DEVICE_ID_VF_DCS_1_X
     - PCI_VENDOR_ID_INTEL 0x8086
     - 0x09c5

   * - PCIE_DEVICE_ID_INTEL_PAC_N3000
     - PCI_VENDOR_ID_INTEL 0x8086
     - 0x0b30

   * - PCIE_DEVICE_ID_INTEL_PAC_D5005
     - PCI_VENDOR_ID_INTEL 0x8086
     - 0x0b2b

   * - PCIE_DEVICE_ID_INTEL_PAC_D5005_VF
     - PCI_VENDOR_ID_INTEL 0x8086
     - 0x0b2c

   * - PCIE_DEVICE_ID_SILICOM_PAC_N5010
     - PCI_VENDOR_ID_SILICOM_DENMARK 0x1c2c
     - 0x1000

   * - PCIE_DEVICE_ID_SILICOM_PAC_N5011
     - PCI_VENDOR_ID_SILICOM_DENMARK 0x1c2c
     - 0x1001

.. list-table:: PCI VID/PID pending acceptance into kernel.org for the dfl-pci driver
   :widths: 2 2 2
   :header-rows: 1

   * - Macro
     - Vendor ID
     - Product ID

   * - PCIE_DEVICE_ID_PF_DFL
     - PCI_VENDOR_ID_INTEL 0x8086
     - 0xbcce

   * - PCIE_DEVICE_ID_VF_DFL
     - PCI_VENDOR_ID_INTEL 0x8086
     - 0xbccf

.. list-table:: PCI SVID/SID associated with 8086:bcce and 8086:bccf
   :widths: 2 2 2
   :header-rows: 1

   * - Macro
     - Subsystem Vendor ID
     - Subsystem ID

   * - PCIE_DEVICE_SID_C6100
     - PCI_VENDOR_ID_INTEL 0x8086
     - 0x17d4

   * - PCIE_DEVICE_SID_N6000
     - PCI_VENDOR_ID_INTEL 0x8086
     - 0x1770

   * - PCIE_DEVICE_SID_N6001
     - PCI_VENDOR_ID_INTEL 0x8086
     - 0x1771

