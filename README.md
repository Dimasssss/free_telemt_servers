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

# Server Metrics 2026-03-17 05:18:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 37981.9 (10h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207032
telemt_connections_bad_total 3163
telemt_handshake_timeouts_total 7199
telemt_upstream_connect_attempt_total 8053
telemt_upstream_connect_success_total 8010
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 8053
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3647
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4358
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6123
telemt_me_reconnect_success_total 6101
telemt_me_reader_eof_total 6491
telemt_me_idle_close_by_peer_total 6491
telemt_me_route_drop_no_conn_total 65365
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 187065
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1201
telemt_desync_full_logged_total 416
telemt_desync_suppressed_total 785
telemt_desync_frames_bucket_total{bucket="1_2"} 275
telemt_desync_frames_bucket_total{bucket="3_10"} 608
telemt_desync_frames_bucket_total{bucket="gt_10"} 318
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6160
telemt_me_writer_restored_same_endpoint_total 6080
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 186863
telemt_user_connections_current{user="hello"} 553
telemt_user_octets_from_client{user="hello"} 2623733664 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 84588454592 (78.78 GB)
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 38233.3 (10h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121954
telemt_connections_bad_total 2191
telemt_handshake_timeouts_total 9987
telemt_upstream_connect_attempt_total 10588
telemt_upstream_connect_success_total 10451
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 10588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4349
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6026
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_reconnect_attempts_total 9725
telemt_me_reconnect_success_total 8553
telemt_me_reader_eof_total 9055
telemt_me_idle_close_by_peer_total 9055
telemt_me_route_drop_no_conn_total 47058
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 105238
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 295
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 193
telemt_desync_frames_bucket_total{bucket="1_2"} 71
telemt_desync_frames_bucket_total{bucket="3_10"} 142
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 8670
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 8537
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 105242
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 1374448948 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 45770645240 (42.63 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 38009.7 (10h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73693
telemt_connections_bad_total 1023
telemt_handshake_timeouts_total 2480
telemt_upstream_connect_attempt_total 10197
telemt_upstream_connect_success_total 10142
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 10197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4508
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5572
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 8260
telemt_me_reconnect_success_total 8216
telemt_me_reader_eof_total 8805
telemt_me_idle_close_by_peer_total 8805
telemt_me_route_drop_no_conn_total 24570
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63023
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 42
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 8316
telemt_me_writer_restored_same_endpoint_total 8205
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 63007
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 5947285352 (5.54 GB)
telemt_user_octets_to_client{user="hello"} 20533404044 (19.12 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 38068.7 (10h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121164
telemt_connections_bad_total 3655
telemt_handshake_timeouts_total 3543
telemt_upstream_connect_attempt_total 8700
telemt_upstream_connect_success_total 8626
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 8700
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4535
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_reconnect_attempts_total 6715
telemt_me_reconnect_success_total 6664
telemt_me_reader_eof_total 7100
telemt_me_idle_close_by_peer_total 7100
telemt_me_route_drop_no_conn_total 40763
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 110383
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 202
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 139
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 79
telemt_desync_frames_bucket_total{bucket="gt_10"} 80
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 6762
telemt_me_writer_restored_same_endpoint_total 6657
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 110401
telemt_user_connections_current{user="hello"} 394
telemt_user_octets_from_client{user="hello"} 1225783066 (1.14 GB)
telemt_user_octets_to_client{user="hello"} 52305295929 (48.71 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 38040.7 (10h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92045
telemt_connections_bad_total 24576
telemt_handshake_timeouts_total 1941
telemt_upstream_connect_attempt_total 11329
telemt_upstream_connect_success_total 11180
telemt_upstream_connect_fail_total 149
telemt_upstream_connect_attempts_per_request{bucket="1"} 11329
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5014
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5991
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 149
telemt_me_reconnect_attempts_total 11417
telemt_me_reconnect_success_total 9157
telemt_me_reader_eof_total 9683
telemt_me_idle_close_by_peer_total 9683
telemt_me_route_drop_no_conn_total 24940
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63003
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 9349
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 9149
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 192
telemt_user_connections_total{user="hello"} 63101
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 718076427 (684.81 MB)
telemt_user_octets_to_client{user="hello"} 27043687266 (25.19 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 38201.7 (10h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 227715
telemt_connections_bad_total 29468
telemt_handshake_timeouts_total 1660
telemt_upstream_connect_attempt_total 7883
telemt_upstream_connect_success_total 7842
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 7883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4088
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 5961
telemt_me_reconnect_success_total 5935
telemt_me_reader_eof_total 6368
telemt_me_idle_close_by_peer_total 6368
telemt_me_route_drop_no_conn_total 198203
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 266977
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 211
telemt_desync_full_logged_total 111
telemt_desync_suppressed_total 100
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 6022
telemt_me_writer_restored_same_endpoint_total 5925
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 189229
telemt_user_connections_current{user="hello"} 575
telemt_user_octets_from_client{user="hello"} 2958058392 (2.75 GB)
telemt_user_octets_to_client{user="hello"} 144104375524 (134.21 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 26208.2 (7h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 393
telemt_connections_bad_total 187
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 13145
telemt_upstream_connect_success_total 13145
telemt_upstream_connect_attempts_per_request{bucket="1"} 13145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5538
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 11820
telemt_me_reconnect_success_total 11756
telemt_me_reader_eof_total 12902
telemt_me_idle_close_by_peer_total 12902
telemt_me_route_drop_no_conn_total 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 202
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 11866
telemt_me_writer_restored_same_endpoint_total 11756
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 202
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 158260168 (150.93 MB)
telemt_user_octets_to_client{user="hello"} 92471472 (88.19 MB)
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```