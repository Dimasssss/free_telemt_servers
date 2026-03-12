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

# Server Metrics 2026-03-12 15:21:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 28101.1 (7h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149432
telemt_connections_bad_total 1870
telemt_handshake_timeouts_total 4608
telemt_upstream_connect_attempt_total 6844
telemt_upstream_connect_success_total 6817
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 6844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3056
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3755
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 276
telemt_me_reconnect_attempts_total 5388
telemt_me_reconnect_success_total 5348
telemt_me_reader_eof_total 5634
telemt_me_idle_close_by_peer_total 5633
telemt_me_route_drop_no_conn_total 43231
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 129378
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 590
telemt_desync_full_logged_total 223
telemt_desync_suppressed_total 367
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 228
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 5396
telemt_me_writer_restored_same_endpoint_total 5332
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 129344
telemt_user_connections_current{user="hello"} 294
telemt_user_octets_from_client{user="hello"} 2168894552 (2.02 GB)
telemt_user_octets_to_client{user="hello"} 48603606524 (45.27 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 27993.9 (7h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62917
telemt_connections_bad_total 449
telemt_handshake_timeouts_total 437
telemt_upstream_connect_attempt_total 8659
telemt_upstream_connect_success_total 8467
telemt_upstream_connect_fail_total 191
telemt_upstream_connect_attempts_per_request{bucket="1"} 8658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3410
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5010
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 191
telemt_me_keepalive_timeout_total 186
telemt_me_reconnect_attempts_total 23962
telemt_me_reconnect_success_total 7035
telemt_me_reader_eof_total 7718
telemt_me_idle_close_by_peer_total 7718
telemt_me_route_drop_no_conn_total 27489
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59903
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
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
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 7615
telemt_me_refill_failed_total 528
telemt_me_writer_restored_same_endpoint_total 7020
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 580
telemt_user_connections_total{user="hello"} 59894
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 658370292 (627.87 MB)
telemt_user_octets_to_client{user="hello"} 16801761600 (15.65 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 27957.3 (7h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85046
telemt_connections_bad_total 1432
telemt_handshake_timeouts_total 1583
telemt_upstream_connect_attempt_total 7757
telemt_upstream_connect_success_total 7757
telemt_upstream_connect_attempts_per_request{bucket="1"} 7757
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3988
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 136
telemt_me_reconnect_attempts_total 6339
telemt_me_reconnect_success_total 6285
telemt_me_reader_eof_total 6618
telemt_me_idle_close_by_peer_total 6618
telemt_me_route_drop_no_conn_total 30900
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 78499
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 6335
telemt_me_writer_restored_same_endpoint_total 6265
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 78471
telemt_user_connections_current{user="hello"} 201
telemt_user_octets_from_client{user="hello"} 2071736240 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 42837320000 (39.90 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 27933.2 (7h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115405
telemt_connections_bad_total 10423
telemt_handshake_timeouts_total 799
telemt_upstream_connect_attempt_total 6826
telemt_upstream_connect_success_total 6640
telemt_upstream_connect_fail_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 6826
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3015
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3600
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 186
telemt_me_keepalive_timeout_total 298
telemt_me_reconnect_attempts_total 23711
telemt_me_reconnect_success_total 5226
telemt_me_reader_eof_total 5937
telemt_me_idle_close_by_peer_total 5937
telemt_me_route_drop_no_conn_total 40406
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98054
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 337
telemt_desync_full_logged_total 106
telemt_desync_suppressed_total 231
telemt_desync_frames_bucket_total{bucket="1_2"} 108
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 108
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 5864
telemt_me_refill_failed_total 576
telemt_me_writer_restored_same_endpoint_total 5218
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 638
telemt_user_connections_total{user="hello"} 97937
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 1908421140 (1.78 GB)
telemt_user_octets_to_client{user="hello"} 40525196996 (37.74 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 27902.5 (7h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65174
telemt_connections_bad_total 5400
telemt_handshake_timeouts_total 1064
telemt_upstream_connect_attempt_total 29172
telemt_upstream_connect_success_total 28833
telemt_upstream_connect_fail_total 339
telemt_upstream_connect_attempts_per_request{bucket="1"} 29172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4871
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 339
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 36911
telemt_me_reconnect_success_total 3684
telemt_me_reader_eof_total 4719
telemt_me_idle_close_by_peer_total 4719
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 12528
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33443
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 448
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4745
telemt_me_refill_failed_total 1041
telemt_me_writer_restored_same_endpoint_total 3667
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1061
telemt_user_connections_total{user="hello"} 57179
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 488199113 (465.58 MB)
telemt_user_octets_to_client{user="hello"} 17376831346 (16.18 GB)
telemt_user_msgs_from_client{user="hello"} 371091
telemt_user_msgs_to_client{user="hello"} 1579803
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 27889.8 (7h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173448
telemt_connections_bad_total 898
telemt_handshake_timeouts_total 1385
telemt_upstream_connect_attempt_total 5827
telemt_upstream_connect_success_total 5795
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 5827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3048
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 329
telemt_me_reconnect_attempts_total 4427
telemt_me_reconnect_success_total 4389
telemt_me_reader_eof_total 4606
telemt_me_idle_close_by_peer_total 4605
telemt_me_route_drop_no_conn_total 67480
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165928
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 243
telemt_desync_full_logged_total 95
telemt_desync_suppressed_total 148
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4446
telemt_me_writer_restored_same_endpoint_total 4382
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 165887
telemt_user_connections_current{user="hello"} 426
telemt_user_octets_from_client{user="hello"} 3325542524 (3.10 GB)
telemt_user_octets_to_client{user="hello"} 76213343772 (70.98 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 58
```