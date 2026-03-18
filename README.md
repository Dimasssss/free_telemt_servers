# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-18 09:10:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 1771.7 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86340
telemt_connections_bad_total 229
telemt_handshake_timeouts_total 1867
telemt_upstream_connect_attempt_total 60372
telemt_upstream_connect_success_total 59466
telemt_upstream_connect_fail_total 906
telemt_upstream_connect_attempts_per_request{bucket="1"} 60372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2575
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 582
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 906
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 505811
telemt_me_reconnect_success_total 296
telemt_me_reader_eof_total 199
telemt_me_idle_close_by_peer_total 197
telemt_me_route_drop_no_conn_total 7080
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13257
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 52
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 23
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 12
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 239
telemt_me_refill_failed_total 16481
telemt_me_writer_restored_same_endpoint_total 191
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_user_connections_total{user="hello"} 72259
telemt_user_connections_current{user="hello"} 1662
telemt_user_octets_from_client{user="hello"} 683822651 (652.14 MB)
telemt_user_octets_to_client{user="hello"} 11646849765 (10.85 GB)
telemt_user_msgs_from_client{user="hello"} 788041
telemt_user_msgs_to_client{user="hello"} 1079628
telemt_user_unique_ips_current{user="hello"} 461
telemt_user_unique_ips_recent_window{user="hello"} 304
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 1802.4 (0h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173865
telemt_connections_bad_total 25281
telemt_handshake_timeouts_total 3600
telemt_upstream_connect_attempt_total 343
telemt_upstream_connect_success_total 343
telemt_upstream_connect_attempts_per_request{bucket="1"} 343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 102
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 228
telemt_me_reconnect_success_total 219
telemt_me_reader_eof_total 168
telemt_me_idle_close_by_peer_total 168
telemt_me_route_drop_no_conn_total 60158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 136860
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 619
telemt_desync_full_logged_total 158
telemt_desync_suppressed_total 461
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 249
telemt_desync_frames_bucket_total{bucket="gt_10"} 243
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 189
telemt_me_writer_restored_same_endpoint_total 218
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 136180
telemt_user_connections_current{user="hello"} 3313
telemt_user_octets_from_client{user="hello"} 4987110644 (4.64 GB)
telemt_user_octets_to_client{user="hello"} 42032369676 (39.15 GB)
telemt_user_unique_ips_current{user="hello"} 993
telemt_user_unique_ips_recent_window{user="hello"} 497
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 1717.5 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148522
telemt_connections_bad_total 5950
telemt_handshake_timeouts_total 3053
telemt_upstream_connect_attempt_total 8671
telemt_upstream_connect_success_total 8671
telemt_upstream_connect_attempts_per_request{bucket="1"} 8671
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7220
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1445
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 604678
telemt_me_reconnect_success_total 354
telemt_me_reader_eof_total 270
telemt_me_idle_close_by_peer_total 270
telemt_me_route_drop_no_conn_total 116670
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 113070
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 155
telemt_desync_full_logged_total 66
telemt_desync_suppressed_total 89
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 67
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_me_writer_removed_unexpected_total 298
telemt_me_refill_failed_total 19630
telemt_me_writer_restored_same_endpoint_total 319
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_user_connections_total{user="hello"} 121161
telemt_user_connections_current{user="hello"} 2058
telemt_user_octets_from_client{user="hello"} 674547175 (643.30 MB)
telemt_user_octets_to_client{user="hello"} 20473332084 (19.07 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 604
telemt_user_unique_ips_recent_window{user="hello"} 327
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 1748.2 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153991
telemt_connections_bad_total 3360
telemt_handshake_timeouts_total 16851
telemt_upstream_connect_attempt_total 10967
telemt_upstream_connect_success_total 10889
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 10967
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 810
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_reconnect_attempts_total 2809808
telemt_me_reconnect_success_total 493
telemt_me_reader_eof_total 442
telemt_me_idle_close_by_peer_total 442
telemt_me_route_drop_no_conn_total 50718
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109873
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 216
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 142
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 81
telemt_desync_frames_bucket_total{bucket="gt_10"} 84
telemt_me_writer_removed_unexpected_total 464
telemt_me_refill_failed_total 99529
telemt_me_writer_restored_same_endpoint_total 398
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_user_connections_total{user="hello"} 120107
telemt_user_connections_current{user="hello"} 3393
telemt_user_octets_from_client{user="hello"} 1349884582 (1.26 GB)
telemt_user_octets_to_client{user="hello"} 28119387045 (26.19 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 863
telemt_user_unique_ips_recent_window{user="hello"} 437
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 1642.5 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117569
telemt_connections_bad_total 4713
telemt_handshake_timeouts_total 1019
telemt_upstream_connect_attempt_total 10055
telemt_upstream_connect_success_total 10054
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10055
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 580
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2982383
telemt_me_reconnect_success_total 435
telemt_me_reader_eof_total 356
telemt_me_idle_close_by_peer_total 356
telemt_me_route_drop_no_conn_total 32531
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 89216
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 244
telemt_desync_full_logged_total 91
telemt_desync_suppressed_total 153
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 90
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_me_writer_removed_unexpected_total 378
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 320
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 98675
telemt_user_connections_current{user="hello"} 2669
telemt_user_octets_from_client{user="hello"} 1387144309 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 37328561213 (34.76 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 828
telemt_user_unique_ips_recent_window{user="hello"} 408
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 1527.6 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32609
telemt_connections_bad_total 5135
telemt_handshake_timeouts_total 171
telemt_upstream_connect_attempt_total 240
telemt_upstream_connect_success_total 240
telemt_upstream_connect_attempts_per_request{bucket="1"} 240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 153
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 87
telemt_me_reconnect_attempts_total 120
telemt_me_reconnect_success_total 119
telemt_me_reader_eof_total 84
telemt_me_idle_close_by_peer_total 84
telemt_me_route_drop_no_conn_total 9179
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 25913
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 48
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 105
telemt_me_writer_restored_same_endpoint_total 111
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_user_connections_total{user="hello"} 25908
telemt_user_connections_current{user="hello"} 998
telemt_user_octets_from_client{user="hello"} 679150532 (647.69 MB)
telemt_user_octets_to_client{user="hello"} 5405160416 (5.03 GB)
telemt_user_unique_ips_current{user="hello"} 325
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 1598.6 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89856
telemt_connections_bad_total 540
telemt_handshake_timeouts_total 1555
telemt_upstream_connect_attempt_total 270
telemt_upstream_connect_success_total 257
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 270
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 164
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 86
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 141
telemt_me_reconnect_success_total 132
telemt_me_reader_eof_total 91
telemt_me_idle_close_by_peer_total 91
telemt_me_route_drop_no_conn_total 95387
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 82929
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 220
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 153
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 89
telemt_me_writer_removed_unexpected_total 116
telemt_me_writer_restored_same_endpoint_total 122
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_user_connections_total{user="hello"} 82877
telemt_user_connections_current{user="hello"} 1872
telemt_user_octets_from_client{user="hello"} 901886660 (860.11 MB)
telemt_user_octets_to_client{user="hello"} 30413617388 (28.32 GB)
telemt_user_unique_ips_current{user="hello"} 564
telemt_user_unique_ips_recent_window{user="hello"} 255
```