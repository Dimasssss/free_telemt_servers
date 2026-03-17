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

# Server Metrics 2026-03-17 04:47:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 36137.8 (10h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 192490
telemt_connections_bad_total 2650
telemt_handshake_timeouts_total 7030
telemt_upstream_connect_attempt_total 7706
telemt_upstream_connect_success_total 7662
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 7705
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4173
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5862
telemt_me_reconnect_success_total 5842
telemt_me_reader_eof_total 6214
telemt_me_idle_close_by_peer_total 6214
telemt_me_route_drop_no_conn_total 61113
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 174580
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1120
telemt_desync_full_logged_total 388
telemt_desync_suppressed_total 732
telemt_desync_frames_bucket_total{bucket="1_2"} 255
telemt_desync_frames_bucket_total{bucket="3_10"} 575
telemt_desync_frames_bucket_total{bucket="gt_10"} 290
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 5899
telemt_me_writer_restored_same_endpoint_total 5821
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 174388
telemt_user_connections_current{user="hello"} 489
telemt_user_octets_from_client{user="hello"} 2442197364 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 79798162524 (74.32 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 36388.8 (10h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107528
telemt_connections_bad_total 2139
telemt_handshake_timeouts_total 3636
telemt_upstream_connect_attempt_total 10152
telemt_upstream_connect_success_total 10021
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 10152
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5784
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_reconnect_attempts_total 9381
telemt_me_reconnect_success_total 8211
telemt_me_reader_eof_total 8688
telemt_me_idle_close_by_peer_total 8688
telemt_me_route_drop_no_conn_total 43841
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 97435
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 266
telemt_desync_full_logged_total 91
telemt_desync_suppressed_total 175
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 8324
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 8195
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 97437
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 1321792020 (1.23 GB)
telemt_user_octets_to_client{user="hello"} 44073849744 (41.05 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 36165.4 (10h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69347
telemt_connections_bad_total 977
telemt_handshake_timeouts_total 2414
telemt_upstream_connect_attempt_total 9637
telemt_upstream_connect_success_total 9585
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 9637
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5273
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 7789
telemt_me_reconnect_success_total 7746
telemt_me_reader_eof_total 8297
telemt_me_idle_close_by_peer_total 8297
telemt_me_route_drop_no_conn_total 22996
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59061
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
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 7843
telemt_me_writer_restored_same_endpoint_total 7735
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 59044
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 5905178632 (5.50 GB)
telemt_user_octets_to_client{user="hello"} 19303757508 (17.98 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 36224.5 (10h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112363
telemt_connections_bad_total 3627
telemt_handshake_timeouts_total 3084
telemt_upstream_connect_attempt_total 8335
telemt_upstream_connect_success_total 8264
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 8335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3870
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4339
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_reconnect_attempts_total 6438
telemt_me_reconnect_success_total 6389
telemt_me_reader_eof_total 6806
telemt_me_idle_close_by_peer_total 6806
telemt_me_route_drop_no_conn_total 37845
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 102316
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 179
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 122
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 74
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 6484
telemt_me_writer_restored_same_endpoint_total 6382
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 102335
telemt_user_connections_current{user="hello"} 277
telemt_user_octets_from_client{user="hello"} 1107734790 (1.03 GB)
telemt_user_octets_to_client{user="hello"} 47291868497 (44.04 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 36196.4 (10h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82741
telemt_connections_bad_total 20083
telemt_handshake_timeouts_total 1401
telemt_upstream_connect_attempt_total 10747
telemt_upstream_connect_success_total 10612
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 10747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4754
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5715
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_reconnect_attempts_total 11038
telemt_me_reconnect_success_total 8786
telemt_me_reader_eof_total 9286
telemt_me_idle_close_by_peer_total 9286
telemt_me_route_drop_no_conn_total 23317
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59031
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
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 8974
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 8778
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 59027
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 655851924 (625.47 MB)
telemt_user_octets_to_client{user="hello"} 23272063976 (21.67 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 36357.3 (10h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 215185
telemt_connections_bad_total 29446
telemt_handshake_timeouts_total 1401
telemt_upstream_connect_attempt_total 7577
telemt_upstream_connect_success_total 7537
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 7577
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3930
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 5744
telemt_me_reconnect_success_total 5719
telemt_me_reader_eof_total 6136
telemt_me_idle_close_by_peer_total 6136
telemt_me_route_drop_no_conn_total 192576
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 255930
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 177
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 5801
telemt_me_writer_restored_same_endpoint_total 5709
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 178182
telemt_user_connections_current{user="hello"} 466
telemt_user_octets_from_client{user="hello"} 2787421528 (2.60 GB)
telemt_user_octets_to_client{user="hello"} 138768907228 (129.24 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 24363.9 (6h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183
telemt_connections_bad_total 122
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 12266
telemt_upstream_connect_success_total 12266
telemt_upstream_connect_attempts_per_request{bucket="1"} 12266
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5137
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 11043
telemt_me_reconnect_success_total 10982
telemt_me_reader_eof_total 12049
telemt_me_idle_close_by_peer_total 12049
telemt_me_route_drop_no_conn_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 11086
telemt_me_writer_restored_same_endpoint_total 10982
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 157584760 (150.28 MB)
telemt_user_octets_to_client{user="hello"} 24357516 (23.23 MB)
```