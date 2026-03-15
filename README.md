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

# Server Metrics 2026-03-15 06:18:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 29036.7 (8h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79371
telemt_connections_bad_total 448
telemt_handshake_timeouts_total 1582
telemt_upstream_connect_attempt_total 7159
telemt_upstream_connect_success_total 7116
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 7159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3870
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5670
telemt_me_reconnect_success_total 5650
telemt_me_reader_eof_total 6053
telemt_me_idle_close_by_peer_total 6053
telemt_me_route_drop_no_conn_total 59823
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80707
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 631
telemt_desync_full_logged_total 283
telemt_desync_suppressed_total 348
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 268
telemt_desync_frames_bucket_total{bucket="gt_10"} 254
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 5695
telemt_me_writer_restored_same_endpoint_total 5619
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 74291
telemt_user_connections_current{user="hello"} 340
telemt_user_octets_from_client{user="hello"} 936680600 (893.29 MB)
telemt_user_octets_to_client{user="hello"} 36905232744 (34.37 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 29044.0 (8h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27124
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 111
telemt_upstream_connect_attempt_total 7885
telemt_upstream_connect_success_total 7885
telemt_upstream_connect_attempts_per_request{bucket="1"} 7885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3458
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4420
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6434
telemt_me_reconnect_success_total 6408
telemt_me_reader_eof_total 6893
telemt_me_idle_close_by_peer_total 6893
telemt_me_route_drop_no_conn_total 14015
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 25846
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 6467
telemt_me_writer_restored_same_endpoint_total 6392
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 25849
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 717823312 (684.57 MB)
telemt_user_octets_to_client{user="hello"} 9787595532 (9.12 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 29036.5 (8h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34839
telemt_connections_bad_total 454
telemt_handshake_timeouts_total 1768
telemt_upstream_connect_attempt_total 7775
telemt_upstream_connect_success_total 7774
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4354
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 6327
telemt_me_reconnect_success_total 6300
telemt_me_reader_eof_total 6817
telemt_me_idle_close_by_peer_total 6817
telemt_me_route_drop_no_conn_total 12149
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31468
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 6354
telemt_me_writer_restored_same_endpoint_total 6296
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 31417
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 8768269624 (8.17 GB)
telemt_user_octets_to_client{user="hello"} 17535584616 (16.33 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 29036.4 (8h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36648
telemt_connections_bad_total 129
telemt_handshake_timeouts_total 244
telemt_upstream_connect_attempt_total 6871
telemt_upstream_connect_success_total 6870
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6871
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3202
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3648
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 5429
telemt_me_reconnect_success_total 5409
telemt_me_reader_eof_total 5798
telemt_me_idle_close_by_peer_total 5798
telemt_me_route_drop_no_conn_total 16642
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34024
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 71
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 53
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 5465
telemt_me_writer_restored_same_endpoint_total 5398
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 33943
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 616542676 (587.98 MB)
telemt_user_octets_to_client{user="hello"} 22310372920 (20.78 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 4107.7 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5731
telemt_connections_bad_total 801
telemt_handshake_timeouts_total 56
telemt_upstream_connect_attempt_total 1795
telemt_upstream_connect_success_total 1767
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 1795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 774
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 987
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 95768
telemt_me_reconnect_success_total 1378
telemt_me_reader_eof_total 1353
telemt_me_idle_close_by_peer_total 1353
telemt_me_route_drop_no_conn_total 1475
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4629
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1302
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 1274
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 4774
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 30218429 (28.82 MB)
telemt_user_octets_to_client{user="hello"} 1754300139 (1.63 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 29035.5 (8h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96810
telemt_connections_bad_total 1792
telemt_handshake_timeouts_total 425
telemt_upstream_connect_attempt_total 6424
telemt_upstream_connect_success_total 6387
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 6424
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3207
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3179
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 4938
telemt_me_reconnect_success_total 4915
telemt_me_reader_eof_total 5235
telemt_me_idle_close_by_peer_total 5235
telemt_me_route_drop_no_conn_total 51640
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91899
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 22
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 12
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 4935
telemt_me_writer_restored_same_endpoint_total 4888
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 90457
telemt_user_connections_current{user="hello"} 314
telemt_user_octets_from_client{user="hello"} 2270729672 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 48716109780 (45.37 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 44
```