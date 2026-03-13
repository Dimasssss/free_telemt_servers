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

# Server Metrics 2026-03-13 12:42:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 104950.6 (29h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 429436
telemt_connections_bad_total 3211
telemt_handshake_timeouts_total 8410
telemt_upstream_connect_attempt_total 26642
telemt_upstream_connect_success_total 26516
telemt_upstream_connect_fail_total 126
telemt_upstream_connect_attempts_per_request{bucket="1"} 26642
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11970
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14498
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 126
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2395
telemt_me_reconnect_attempts_total 24780
telemt_me_reconnect_success_total 21255
telemt_me_reader_eof_total 22694
telemt_me_idle_close_by_peer_total 22693
telemt_me_route_drop_no_conn_total 135954
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 373421
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1256
telemt_desync_full_logged_total 447
telemt_desync_suppressed_total 809
telemt_desync_frames_bucket_total{bucket="1_2"} 255
telemt_desync_frames_bucket_total{bucket="3_10"} 462
telemt_desync_frames_bucket_total{bucket="gt_10"} 539
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 21586
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 21239
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 331
telemt_user_connections_total{user="hello"} 373013
telemt_user_connections_current{user="hello"} 345
telemt_user_octets_from_client{user="hello"} 6720958608 (6.26 GB)
telemt_user_octets_to_client{user="hello"} 160290934076 (149.28 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 104843.6 (29h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 198515
telemt_connections_bad_total 1659
telemt_handshake_timeouts_total 1481
telemt_upstream_connect_attempt_total 60006
telemt_upstream_connect_success_total 59298
telemt_upstream_connect_fail_total 708
telemt_upstream_connect_attempts_per_request{bucket="1"} 60006
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37732
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20982
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 584
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 708
telemt_me_keepalive_timeout_total 1369
telemt_me_reconnect_attempts_total 98357
telemt_me_reconnect_success_total 25964
telemt_me_reader_eof_total 28986
telemt_me_idle_close_by_peer_total 28986
telemt_me_route_drop_no_conn_total 79233
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159428
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 28450
telemt_me_refill_failed_total 2258
telemt_me_writer_restored_same_endpoint_total 25947
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2486
telemt_user_connections_total{user="hello"} 187295
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 1904602377 (1.77 GB)
telemt_user_octets_to_client{user="hello"} 61700441222 (57.46 GB)
telemt_user_msgs_from_client{user="hello"} 418875
telemt_user_msgs_to_client{user="hello"} 3041138
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 104807.3 (29h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 241346
telemt_connections_bad_total 2065
telemt_handshake_timeouts_total 8112
telemt_upstream_connect_attempt_total 28408
telemt_upstream_connect_success_total 28404
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 28408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13152
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15225
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2207
telemt_me_reconnect_attempts_total 24318
telemt_me_reconnect_success_total 23106
telemt_me_reader_eof_total 24756
telemt_me_idle_close_by_peer_total 24756
telemt_me_route_drop_no_conn_total 89474
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 222406
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 92
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 23360
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 23086
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 222320
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 9392569908 (8.75 GB)
telemt_user_octets_to_client{user="hello"} 98184905212 (91.44 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 104782.9 (29h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 336889
telemt_connections_bad_total 15024
telemt_handshake_timeouts_total 2488
telemt_upstream_connect_attempt_total 40195
telemt_upstream_connect_success_total 30115
telemt_upstream_connect_fail_total 10080
telemt_upstream_connect_attempts_per_request{bucket="1"} 40195
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15206
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14697
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 203
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10080
telemt_me_keepalive_timeout_total 4080
telemt_me_reconnect_attempts_total 93365
telemt_me_reconnect_success_total 21813
telemt_me_reader_eof_total 24711
telemt_me_idle_close_by_peer_total 24704
telemt_me_route_drop_no_conn_total 121412
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 290150
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1025
telemt_desync_full_logged_total 303
telemt_desync_suppressed_total 722
telemt_desync_frames_bucket_total{bucket="1_2"} 250
telemt_desync_frames_bucket_total{bucket="3_10"} 382
telemt_desync_frames_bucket_total{bucket="gt_10"} 393
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 24319
telemt_me_refill_failed_total 2231
telemt_me_writer_restored_same_endpoint_total 21803
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2506
telemt_user_connections_total{user="hello"} 293061
telemt_user_connections_current{user="hello"} 236
telemt_user_octets_from_client{user="hello"} 5975138034 (5.56 GB)
telemt_user_octets_to_client{user="hello"} 110370473689 (102.79 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 54954.5 (15h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80518
telemt_connections_bad_total 10843
telemt_handshake_timeouts_total 1183
telemt_upstream_connect_attempt_total 23606
telemt_upstream_connect_success_total 23421
telemt_upstream_connect_fail_total 185
telemt_upstream_connect_attempts_per_request{bucket="1"} 23606
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12428
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10929
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 185
telemt_me_keepalive_timeout_total 964
telemt_me_reconnect_attempts_total 25671
telemt_me_reconnect_success_total 15754
telemt_me_reader_eof_total 16909
telemt_me_idle_close_by_peer_total 16909
telemt_me_route_drop_no_conn_total 23832
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60989
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 123
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 16202
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 15736
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 448
telemt_user_connections_total{user="hello"} 65898
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 568385105 (542.05 MB)
telemt_user_octets_to_client{user="hello"} 18309393359 (17.05 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 104739.4 (29h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 600798
telemt_connections_bad_total 17656
telemt_handshake_timeouts_total 14981
telemt_upstream_connect_attempt_total 22239
telemt_upstream_connect_success_total 22124
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 22239
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10382
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11717
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 2502
telemt_me_reconnect_attempts_total 21521
telemt_me_reconnect_success_total 16899
telemt_me_reader_eof_total 18140
telemt_me_idle_close_by_peer_total 18137
telemt_me_route_drop_no_conn_total 295630
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 574653
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 471
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 295
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 17261
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 16892
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 362
telemt_user_connections_total{user="hello"} 547702
telemt_user_connections_current{user="hello"} 418
telemt_user_octets_from_client{user="hello"} 9757921620 (9.09 GB)
telemt_user_octets_to_client{user="hello"} 291250876332 (271.25 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 64
```