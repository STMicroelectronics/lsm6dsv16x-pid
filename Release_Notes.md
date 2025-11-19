---
pagetitle: Release Notes for LSM6DSV16X Component
lang: en
header-includes: <link rel="icon" type="image/x-icon" href="_htmresc/favicon.png" />
---

::: {.row}
::: {.col-sm-12 .col-lg-4}

<center>
# Release Notes for LSM6DSV16X Component Driver
Copyright &copy; 2022 STMicroelectronics\

[![ST logo](_htmresc/st_logo_2020.png)](https://www.st.com){.logo}
</center>

# License

This software component is licensed by ST under BSD 3-Clause license, the "License".
You may not use this component except in compliance with the License. You may obtain a copy of the License at:

[BSD 3-Clause license](https://opensource.org/licenses/BSD-3-Clause)

# Purpose

This directory contains the LSM6DSV16X component drivers.
:::

::: {.col-sm-12 .col-lg-8}
# Update history

::: {.collapse}
<input type="checkbox" id="collapse-section1" aria-hidden="true">
<label for="collapse-section1" aria-hidden="true">V1.0.0 / 03-Aug-2022</label>
<div>

## Main changes

### First release

- First official release [ref. DS v1.0]

##

</div>

<input type="checkbox" id="collapse-section2" aria-hidden="true">
<label for="collapse-section2" aria-hidden="true">V2.0.0 / 22-Nov-2022</label>
<div>

## Main changes

- First official release [ref. DS v2.0]

##

</div>

<input type="checkbox" id="collapse-section3" aria-hidden="true">
<label for="collapse-section3" aria-hidden="true">V2.1.0 / 15-May-2023</label>
<div>

## Main changes

- change fifo_batch_sh_slave_xxx() API name
- sensor_hub: add sh_status_get() API
- sensor_hub: change sh_read_data_raw_get() API signature
- review read/write reg ret value checks

##

</div>

<input type="checkbox" id="collapse-section4" aria-hidden="true">
<label for="collapse-section4" aria-hidden="true">V2.1.1 / 18-May-2023</label>
<div>

## Main changes

- read sh status from mainpage

##

</div>

<input type="checkbox" id="collapse-section5" aria-hidden="true">
<label for="collapse-section5" aria-hidden="true">V2.2.0 / 23-May-2023</label>
<div>

## Main changes

- Use a single lsm6dsv16x_sh_slv_cfg_read() API for all targets
- Use a single lsm6dsv16x_fifo_sh_batch_slave_xxx() API for all targets
- Fix MISRA errors

##

</div>

<input type="checkbox" id="collapse-section6" aria-hidden="true">
<label for="collapse-section6" aria-hidden="true">V2.2.1 / 25-July-2023</label>
<div>

## Main changes

- ah_qvar: Add API to convert from LSB to mV
- Fix gyro FS 4000dps value typo error

##

</div>

<input type="checkbox" id="collapse-section7" aria-hidden="true">
<label for="collapse-section7" aria-hidden="true">V3.0.0 / 20-Mar-2024</label>
<div>

## Main changes

- Fixed code style (Artistic Style Version 3.4.13)
- Fix code style
- small code cleaning
- Add "const" to ctx arg for all APIs
- Support routing of drdy_temp to INT2
- Fix typo in lsm5dsv16x_fsm_mode_set condition
- Fix bug in lsm6dsv16x_reg.c

##

</div>

<input type="checkbox" id="collapse-section8" aria-hidden="true">
<label for="collapse-section8" aria-hidden="true">V3.0.1 / 02-May-2024</label>
<div>

## Main changes

- Fix BDR counter regsters get/set APIs
- updated README.md file with tag reference and mdelay description

##

</div>

<input type="checkbox" id="collapse-section9" aria-hidden="true">
<label for="collapse-section9" aria-hidden="true">V3.1.0 / 22-May-2024</label>
<div>

## Main changes

- Add i3c_int_en set/get APIs
- Fix enum mode macros in den_conf_t struct

##

</div>

<input type="checkbox" id="collapse-section10" aria-hidden="true">
<label for="collapse-section10" aria-hidden="true">V4.0.0 / 22-Jun-2024</label>
<div>

## Main changes

- Add defs for num_phy routines

##

</div>

<input type="checkbox" id="collapse-section11" aria-hidden="true">
<label for="collapse-section11" aria-hidden="true">V4.1.0 / 03-Oct-2024</label>
<div>

## Main changes

- Add int2_drdy_ah_qvar event routing on INT2 pin

##

</div>

<input type="checkbox" id="collapse-section12" aria-hidden="true">
<label for="collapse-section12" aria-hidden="true">V4.2.0 / 25-Oct-2024</label>
<div>

## Main changes

- added struct types to help parsing FIFO data
- Complete APIs for handling embedded functions
- simplify efficiently the fifo_read API

##

</div>

<input type="checkbox" id="collapse-section13" aria-hidden="true">
<label for="collapse-section13" aria-hidden="true">V4.3.0 / 18-Dec-2024</label>
<div>

## Main changes

- Move fifo_tag out of struct fifo_out_raw
- Add API to transform float16 to float32

##

</div>

<input type="checkbox" id="collapse-section14" aria-hidden="true">
<label for="collapse-section14" aria-hidden="true">V4.4.0 / 07-Jul-2025</label>
<div>

## Main changes

- Fix driver formatting options
- Added pointer to private data in stmdev_ctx_t

##

</div>

<input type="checkbox" id="collapse-section15" aria-hidden="true">
<label for="collapse-section15" aria-hidden="true">V5.0.0 / 06-Oct-2025</label>
<div>

## Main changes

- Added comments on reset_t enum
- Fix reset_set API: fields boot and sw_reset were wrongly set
- Add enum `fifo_event_t` for stop_on_wtm_set/get functions
- int1/int2 route_get API: init to 0 the returned struct
- Adding CODE_OF_CONDUCT.md and SECURITY.md

##

</div>

<input type="checkbox" id="collapse-section16" aria-hidden="true">
<label for="collapse-section16" aria-hidden="true">V6.0.0 / 05-Nov-2025</label>
<div>

## Main changes

- Added checks before writes and membank setting
- split reset into 3 routines (reboot, sw_por, reset)
- (FIX) move memset in pin_int2_route_get() API

##

</div>

<input type="checkbox" id="collapse-section17" checked aria-hidden="true">
<label for="collapse-section17" aria-hidden="true">V6.0.1 / 19-Nov-2025</label>
<div>

## Main changes

- (fix) do not jump to exit before initing master_config

##

</div>
:::


:::
:::

<footer class="sticky">
::: {.columns}
::: {.column width="95%"}
For complete documentation on LSM6DSV16X,
visit:
[LSM6DSV16X](https://www.st.com/content/st_com/en/products/mems-and-sensors/inemo-inertial-modules/lsm6dsv16x.html)
:::
::: {.column width="5%"}
<abbr title="Based on template cx566953 version 1.0">Info</abbr>
:::
:::
</footer>
