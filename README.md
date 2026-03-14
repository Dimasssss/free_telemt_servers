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

# Server Metrics 2026-03-14 02:27:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 154460.0 (42h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 603009
telemt_connections_bad_total 22576
telemt_handshake_timeouts_total 12915
telemt_upstream_connect_attempt_total 39447
telemt_upstream_connect_success_total 39252
telemt_upstream_connect_fail_total 195
telemt_upstream_connect_attempts_per_request{bucket="1"} 39447
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21139
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 195
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5510
telemt_me_reconnect_attempts_total 35837
telemt_me_reconnect_success_total 31160
telemt_me_reader_eof_total 33288
telemt_me_idle_close_by_peer_total 33287
telemt_me_route_drop_no_conn_total 197774
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 516346
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1673
telemt_desync_full_logged_total 576
telemt_desync_suppressed_total 1097
telemt_desync_frames_bucket_total{bucket="1_2"} 357
telemt_desync_frames_bucket_total{bucket="3_10"} 631
telemt_desync_frames_bucket_total{bucket="gt_10"} 685
telemt_pool_swap_total 140
telemt_me_writer_removed_unexpected_total 31647
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 31144
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 487
telemt_user_connections_total{user="hello"} 516237
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 15615284694 (14.54 GB)
telemt_user_octets_to_client{user="hello"} 254070033956 (236.62 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 154353.8 (42h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 308868
telemt_connections_bad_total 2249
telemt_handshake_timeouts_total 1941
telemt_upstream_connect_attempt_total 144210
telemt_upstream_connect_success_total 143071
telemt_upstream_connect_fail_total 1139
telemt_upstream_connect_attempts_per_request{bucket="1"} 144210
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 107514
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33142
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1139
telemt_me_keepalive_timeout_total 3812
telemt_me_reconnect_attempts_total 163004
telemt_me_reconnect_success_total 32054
telemt_me_reader_eof_total 36976
telemt_me_idle_close_by_peer_total 36976
telemt_me_route_drop_no_conn_total 97740
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 189741
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 36443
telemt_me_refill_failed_total 4086
telemt_me_writer_restored_same_endpoint_total 32037
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4389
telemt_user_connections_total{user="hello"} 292853
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 3054279943 (2.84 GB)
telemt_user_octets_to_client{user="hello"} 91620284523 (85.33 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 154317.4 (42h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 361331
telemt_connections_bad_total 2829
telemt_handshake_timeouts_total 33408
telemt_upstream_connect_attempt_total 40968
telemt_upstream_connect_success_total 40962
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 40968
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18720
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22185
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3297
telemt_me_reconnect_attempts_total 34489
telemt_me_reconnect_success_total 33220
telemt_me_reader_eof_total 35702
telemt_me_idle_close_by_peer_total 35702
telemt_me_route_drop_no_conn_total 128989
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 312538
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 145
telemt_me_writer_removed_unexpected_total 33611
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 33200
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 391
telemt_user_connections_total{user="hello"} 312368
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 12627833796 (11.76 GB)
telemt_user_octets_to_client{user="hello"} 127198217124 (118.46 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 154293.1 (42h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 462610
telemt_connections_bad_total 15378
telemt_handshake_timeouts_total 4376
telemt_upstream_connect_attempt_total 70050
telemt_upstream_connect_success_total 59575
telemt_upstream_connect_fail_total 10475
telemt_upstream_connect_attempts_per_request{bucket="1"} 70050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35854
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23387
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 325
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10475
telemt_me_keepalive_timeout_total 5103
telemt_me_reconnect_attempts_total 138883
telemt_me_reconnect_success_total 32841
telemt_me_reader_eof_total 37102
telemt_me_idle_close_by_peer_total 37094
telemt_me_route_drop_no_conn_total 163720
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 392255
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1708
telemt_desync_full_logged_total 501
telemt_desync_suppressed_total 1207
telemt_desync_frames_bucket_total{bucket="1_2"} 400
telemt_desync_frames_bucket_total{bucket="3_10"} 646
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 36544
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 32831
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3703
telemt_user_connections_total{user="hello"} 411088
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 9083880531 (8.46 GB)
telemt_user_octets_to_client{user="hello"} 158712297000 (147.81 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 104464.8 (29h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 174655
telemt_connections_bad_total 25254
telemt_handshake_timeouts_total 1564
telemt_upstream_connect_attempt_total 38079
telemt_upstream_connect_success_total 37730
telemt_upstream_connect_fail_total 349
telemt_upstream_connect_attempts_per_request{bucket="1"} 38079
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18484
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 349
telemt_me_keepalive_timeout_total 1404
telemt_me_reconnect_attempts_total 41044
telemt_me_reconnect_success_total 27627
telemt_me_reader_eof_total 29555
telemt_me_idle_close_by_peer_total 29555
telemt_me_route_drop_no_conn_total 51780
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 138032
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 619
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 474
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 28296
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 27609
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 669
telemt_user_connections_total{user="hello"} 142811
telemt_user_connections_current{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 2010913045 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 64969976615 (60.51 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 154249.1 (42h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 890437
telemt_connections_bad_total 27745
telemt_handshake_timeouts_total 25353
telemt_upstream_connect_attempt_total 31977
telemt_upstream_connect_success_total 31807
telemt_upstream_connect_fail_total 170
telemt_upstream_connect_attempts_per_request{bucket="1"} 31977
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16874
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 170
telemt_me_keepalive_timeout_total 3497
telemt_me_reconnect_attempts_total 28826
telemt_me_reconnect_success_total 24159
telemt_me_reader_eof_total 25894
telemt_me_idle_close_by_peer_total 25891
telemt_me_route_drop_no_conn_total 424519
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 832349
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 708
telemt_desync_full_logged_total 231
telemt_desync_suppressed_total 477
telemt_desync_frames_bucket_total{bucket="1_2"} 253
telemt_desync_frames_bucket_total{bucket="3_10"} 231
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 144
telemt_me_writer_removed_unexpected_total 24619
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 24152
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 460
telemt_user_connections_total{user="hello"} 805106
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 14258224524 (13.28 GB)
telemt_user_octets_to_client{user="hello"} 409273940660 (381.17 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 31
```