.. SPDX-License-Identifier: GPL-2.0

========================================
Device Feature List (DFL) Feature Ids
========================================

Individual DFL drivers are bound DFL devices based on Feature Type and
Feature ID.  The table below lists the currently used Type/ID pairs.
New Type/ID pairs can be reserved by submitting a pull request to this
document.


.. list-table:: DFL Feature Type/IDs
   :widths: 2 2 2
   :header-rows: 1

   * - Feature Name
     - Feature Type
     - Feature ID

   * - Thermal Mgmt (legacy)
     - 0
     - 1

   * - Power Mgmt (legacy)
     - 0
     - 2

   * - IPERF
     - 0
     - 3

   * - Global Errors
     - 0
     - 4

   * - Partial Reconfiguration IP
     - 0
     - 5

   * - HSSI (legacy, not used)
     - 0
     - 6

   * - Global Dperf
     - 0
     - 7

   * - QSPI Flash
     - 0
     - 8

   * - External Memory Interface (EMIF)
     - 0
     - 9

   * - dfl_d5005_hssi (deprecated and not to be upstreamed)
     - 0
     - 0xa

   * - dfl_n3000_nios
     - 0
     - 0xd

   * - dfl_spi_altera
     - 0
     - 0xe

   * - n3000 mac rom
     - 0
     - 0xf

   * - s10hssi-EA-R1(duplicate id, rejected netdev implementation, and deprecated)
     - 0
     - 0xf

   * - n3000 Ethernet Group
     - 0
     - 0x10

   * - Trusted Compute Module (TCM) 
     - 0
     - 0x11

   * - PMCI Subsystem
     - 0
     - 0x12

   * - QSFP Subsystem
     - 0
     - 0x13

   * - ST2MM
     - 0
     - 0x14

   * - HSSI Subsystem
     - 0
     - 0x15

   * - n5010 HSSI
     - 0
     - 0x1f

   * - PCIe Subsystem
     - 0
     - 0x20

   * - n5010 Hitek MAC
     - 0
     - 0x21

   * - ToD
     - 0
     - 0x22

   * - Feature with GUID
     - 0
     - 0x23

   * - Virtual UART 
     - 0
     - 0x24

   * - CXL Cache IP
     - 0
     - 0x25

   * - Scalable Scatter-Gather DMA Intel FPGA IP 
     - 0
     - 0x26

   * - Port Errors
     - 1
     - 0x10

   * - Port Umsg
     - 1
     - 0x11

   * - Port User Interrupt
     - 1
     - 0x12

   * - Port Signal Tap
     - 1
     - 0x13

   * - s10 IOPLL
     - 1
     - 0x14
