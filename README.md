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

# Server Metrics 2026-03-13 02:00:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 66443.7 (18h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 267783
telemt_connections_bad_total 2806
telemt_handshake_timeouts_total 5634
telemt_upstream_connect_attempt_total 16807
telemt_upstream_connect_success_total 16736
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 16807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7401
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9289
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1514
telemt_me_reconnect_attempts_total 16875
telemt_me_reconnect_success_total 13396
telemt_me_reader_eof_total 14301
telemt_me_idle_close_by_peer_total 14300
telemt_me_route_drop_no_conn_total 82919
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 222442
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 734
telemt_desync_full_logged_total 277
telemt_desync_suppressed_total 457
telemt_desync_frames_bucket_total{bucket="1_2"} 132
telemt_desync_frames_bucket_total{bucket="3_10"} 272
telemt_desync_frames_bucket_total{bucket="gt_10"} 330
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 13650
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 13380
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 222209
telemt_user_connections_current{user="hello"} 218
telemt_user_octets_from_client{user="hello"} 3969584068 (3.70 GB)
telemt_user_octets_to_client{user="hello"} 110381135052 (102.80 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 66336.6 (18h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124321
telemt_connections_bad_total 739
telemt_handshake_timeouts_total 977
telemt_upstream_connect_attempt_total 36836
telemt_upstream_connect_success_total 36386
telemt_upstream_connect_fail_total 450
telemt_upstream_connect_attempts_per_request{bucket="1"} 36836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22660
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13225
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 501
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 450
telemt_me_keepalive_timeout_total 473
telemt_me_reconnect_attempts_total 60778
telemt_me_reconnect_success_total 16564
telemt_me_reader_eof_total 18407
telemt_me_idle_close_by_peer_total 18407
telemt_me_route_drop_no_conn_total 44469
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 101526
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 18067
telemt_me_refill_failed_total 1380
telemt_me_writer_restored_same_endpoint_total 16549
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1503
telemt_user_connections_total{user="hello"} 118026
telemt_user_connections_current{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 1255907876 (1.17 GB)
telemt_user_octets_to_client{user="hello"} 35515728787 (33.08 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 66300.2 (18h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149810
telemt_connections_bad_total 1730
telemt_handshake_timeouts_total 2366
telemt_upstream_connect_attempt_total 18278
telemt_upstream_connect_success_total 18276
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 18278
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9771
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 369
telemt_me_reconnect_attempts_total 16070
telemt_me_reconnect_success_total 14912
telemt_me_reader_eof_total 15945
telemt_me_idle_close_by_peer_total 15945
telemt_me_route_drop_no_conn_total 57119
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140117
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 52
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 15079
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 14892
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 140069
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 2706965708 (2.52 GB)
telemt_user_octets_to_client{user="hello"} 66657635184 (62.08 GB)
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 66276.1 (18h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 213938
telemt_connections_bad_total 13353
telemt_handshake_timeouts_total 1428
telemt_upstream_connect_attempt_total 30585
telemt_upstream_connect_success_total 20804
telemt_upstream_connect_fail_total 9781
telemt_upstream_connect_attempts_per_request{bucket="1"} 30585
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10587
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10053
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 156
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9781
telemt_me_keepalive_timeout_total 3227
telemt_me_reconnect_attempts_total 51515
telemt_me_reconnect_success_total 14615
telemt_me_reader_eof_total 16267
telemt_me_idle_close_by_peer_total 16260
telemt_me_route_drop_no_conn_total 77296
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177442
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 499
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 356
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 15975
telemt_me_refill_failed_total 1149
telemt_me_writer_restored_same_endpoint_total 14605
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1360
telemt_user_connections_total{user="hello"} 180194
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 3046433126 (2.84 GB)
telemt_user_octets_to_client{user="hello"} 73725033389 (68.66 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 16447.6 (4h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14671
telemt_connections_bad_total 3094
telemt_handshake_timeouts_total 27
telemt_upstream_connect_attempt_total 5113
telemt_upstream_connect_success_total 5067
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 5113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2814
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 4225
telemt_me_reconnect_success_total 4212
telemt_me_reader_eof_total 4515
telemt_me_idle_close_by_peer_total 4515
telemt_me_route_drop_no_conn_total 4449
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11095
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 4246
telemt_me_writer_restored_same_endpoint_total 4196
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 11095
telemt_user_connections_current{user="hello"} 53
telemt_user_octets_from_client{user="hello"} 58412080 (55.71 MB)
telemt_user_octets_to_client{user="hello"} 5954448600 (5.55 GB)
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 66232.3 (18h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 359590
telemt_connections_bad_total 6619
telemt_handshake_timeouts_total 2790
telemt_upstream_connect_attempt_total 14085
telemt_upstream_connect_success_total 14006
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 14085
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7433
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 1346
telemt_me_reconnect_attempts_total 14323
telemt_me_reconnect_success_total 10702
telemt_me_reader_eof_total 11488
telemt_me_idle_close_by_peer_total 11486
telemt_me_route_drop_no_conn_total 160981
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 351576
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 301
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 114
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 10948
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 10695
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 246
telemt_user_connections_total{user="hello"} 339868
telemt_user_connections_current{user="hello"} 240
telemt_user_octets_from_client{user="hello"} 5754162572 (5.36 GB)
telemt_user_octets_to_client{user="hello"} 191506561524 (178.35 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 36
```