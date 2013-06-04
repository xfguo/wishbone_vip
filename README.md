# Wishbone Verification IP

The Wishbone Verification IP is a simple solution for verification of Wishbone B3 master and slave devices. The provided Wishbone verification package includes master and slave SystemVerilog verification IPs and examples. It will help engineers to quickly create verification environment end test their Wishbone master and slave devices.

## Features

 * Free SystemVerilog source code
 * Easy integration and usage
 * Compliant to Wishbone B3 Protocol
 * Operates as a Master or Slave
 * Supports 1, 2, 4 and 8 bytes data block size
 * Supports single cycle transfers
 * Supports wait states injection
 * Supports programmable retry and error insertion
 * Supports full random timings
 * Supports misaligned transfers

## Limitations

 * Doesn’t support TAGs
 * Doesn’t support Lock signal

## Installation

Download or checkout Wishbone Verification IP and unpack it.

If you want to run examples. Go to the following folder: 

    <unpack_dir>/wishbone_vip/examples/sim

For VCS type the following command: 

    vcs -f file_list.f -sverilog

For QuestaSim6.4 type the following command: 

    qverilog -f file_list.f

Please read the Wishbone Verification IP User Manual.

----

Note: This readme description and project is copied and modified from http://syswip.com/wishbone-verification-ip .

