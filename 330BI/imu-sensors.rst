OpenIMU330BI Sensors
====================

.. contents:: Contents
    :local:

.. role:: raw-html(raw)
    :format: html

.. envvar:: ANGULAR RATE

+-----------------------+-----------------------+
| **Specification**     |                       |
|                       |                       |
|                       |                       |
+-----------------------+-----------------------+
| Range: X,Y,Z          | > 400                 |
| (|deg|/Sec)           |                       |
+-----------------------+-----------------------+
| Bias Instability      | < 2                   |
| (|deg|/Hr)            |                       |
| :sup:`1,2`            |                       |
+-----------------------+-----------------------+
| Bias Stability        | < 0.5                 |
| Over Temperature      |                       |
| (|deg|/Sec)           |                       |
| :sup:`3`              |                       |
+-----------------------+-----------------------+
| Resolution (|deg|/Sec)| < 0.02                |
+-----------------------+-----------------------+
| Scale Factor Accuracy | < 0.02                |
| (%)                   |                       |
+-----------------------+-----------------------+
| Angle Random Walk     | < 0.2                 |
| (|deg|/\              |                       |
| :raw-html:`&radic;`\  |                       |
| hr)                   |                       |
+-----------------------+-----------------------+
| Bandwidth (Hz)        | 5-50Hz                |
|                       | (Configurable)        |
+-----------------------+-----------------------+

**Notes:**
:sup:`1` Allen Variance Curve, Constant Temperature,
:sup:`2` 1-Sigma Error,
:sup:`3` RMS Error over Temperature

.. envvar:: ACCELERATION

+-----------------------+-----------------------+
| **Specification**     |                       |
|                       |                       |
|                       |                       |
+-----------------------+-----------------------+
| Range: X,Y,Z          | > 8                   |
| (g)                   |                       |
+-----------------------+-----------------------+
| Bias Instability      | < 20                  |
| (:raw-html:`&micro;`\ |                       |
| g)                    |                       |
| :sup:`1,2`            |                       |
+-----------------------+-----------------------+
| Bias Stability        | < 5                   |
| Over Temperature      |                       |
| (mg)                  |                       |
| :sup:`3`              |                       |
+-----------------------+-----------------------+
| Resolution (mg)       | < 0.5                 |
+-----------------------+-----------------------+
| Scale Factor Accuracy | < 0.1                 |
| (%)                   |                       |
+-----------------------+-----------------------+
| Non-Linearity (%)     | < 0.1                 |
+-----------------------+-----------------------+
| Velocity Random Walk  | < 0.04                |
| (m/s/\                |                       |
| :raw-html:`&radic;`\  |                       |
| hr)                   |                       |
+-----------------------+-----------------------+
| Bandwidth (Hz)        | 5-50Hz                |
|                       | (Configurable)        |
+-----------------------+-----------------------+

**Notes:**
:sup:`1` Allen Variance Curve, Constant Temperature,
:sup:`2` 1-Sigma Error,
:sup:`3` RMS Error over Temperature



.. note::

    This product has been developed and is sold exclusively for commercial applications.
    Military usage is prohibited by the manufacturer.

.. note::

    This product is subject to US Department of Commerce Export Controls ECCN 7A994, ECCN6A996. Any use of this product for nuclear, chemical or biological weapons, or weapons research, or for any use in missiles, rockets, and/or UAV’s of 300km or greater range, or any other activity prohibited by the Export Administration Regulations, is expressly prohibited without the written consent and without obtaining appropriate US export license(s) when required by US law. Diversion contrary to U.S. law is prohibited. Specifications are subject to change without notice.

.. include:: <isonum.txt>
