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

# Server Metrics 2026-03-15 18:17:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 72181.7 (20h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 339199
telemt_connections_bad_total 4198
telemt_handshake_timeouts_total 11037
telemt_upstream_connect_attempt_total 17516
telemt_upstream_connect_success_total 17428
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 17516
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7725
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9667
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 17204
telemt_me_reconnect_success_total 13806
telemt_me_reader_eof_total 14707
telemt_me_idle_close_by_peer_total 14707
telemt_me_route_drop_no_conn_total 463756
telemt_me_route_drop_channel_closed_total 76
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 371934
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1871
telemt_desync_full_logged_total 743
telemt_desync_suppressed_total 1128
telemt_desync_frames_bucket_total{bucket="1_2"} 354
telemt_desync_frames_bucket_total{bucket="3_10"} 731
telemt_desync_frames_bucket_total{bucket="gt_10"} 786
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 14060
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 13772
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 311034
telemt_user_connections_current{user="hello"} 356
telemt_user_octets_from_client{user="hello"} 6360445424 (5.92 GB)
telemt_user_octets_to_client{user="hello"} 243775088708 (227.03 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 72188.7 (20h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135747
telemt_connections_bad_total 2835
telemt_handshake_timeouts_total 12284
telemt_upstream_connect_attempt_total 19558
telemt_upstream_connect_success_total 19558
telemt_upstream_connect_attempts_per_request{bucket="1"} 19558
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10884
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 320
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 18261
telemt_me_reconnect_success_total 15895
telemt_me_reader_eof_total 16996
telemt_me_idle_close_by_peer_total 16995
telemt_me_route_drop_no_conn_total 56476
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 115072
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 16177
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 15879
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 282
telemt_user_connections_total{user="hello"} 115052
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 2142888152 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 57439397816 (53.49 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 72180.7 (20h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139832
telemt_connections_bad_total 1699
telemt_handshake_timeouts_total 3285
telemt_upstream_connect_attempt_total 21108
telemt_upstream_connect_success_total 21100
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 21108
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11905
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 24781
telemt_me_reconnect_success_total 17423
telemt_me_reader_eof_total 18706
telemt_me_idle_close_by_peer_total 18706
telemt_me_route_drop_no_conn_total 54644
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 123034
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 59
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 17820
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 17415
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 397
telemt_user_connections_total{user="hello"} 122926
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 10734203080 (10.00 GB)
telemt_user_octets_to_client{user="hello"} 68643280128 (63.93 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 72180.6 (20h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 192385
telemt_connections_bad_total 963
telemt_handshake_timeouts_total 1298
telemt_upstream_connect_attempt_total 17111
telemt_upstream_connect_success_total 17098
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 17111
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8845
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 13561
telemt_me_reconnect_success_total 13477
telemt_me_reader_eof_total 14348
telemt_me_idle_close_by_peer_total 14348
telemt_me_route_drop_no_conn_total 72880
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177349
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 622
telemt_desync_full_logged_total 232
telemt_desync_suppressed_total 390
telemt_desync_frames_bucket_total{bucket="1_2"} 131
telemt_desync_frames_bucket_total{bucket="3_10"} 289
telemt_desync_frames_bucket_total{bucket="gt_10"} 202
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 13641
telemt_me_writer_restored_same_endpoint_total 13466
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 164
telemt_user_connections_total{user="hello"} 177261
telemt_user_connections_current{user="hello"} 257
telemt_user_octets_from_client{user="hello"} 3282999432 (3.06 GB)
telemt_user_octets_to_client{user="hello"} 81400169664 (75.81 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 47251.9 (13h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116156
telemt_connections_bad_total 24002
telemt_handshake_timeouts_total 2463
telemt_upstream_connect_attempt_total 14077
telemt_upstream_connect_success_total 13994
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 14077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7501
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 105889
telemt_me_reconnect_success_total 11443
telemt_me_reader_eof_total 12021
telemt_me_idle_close_by_peer_total 12021
telemt_me_route_drop_no_conn_total 39785
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 86485
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 270
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 214
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 127
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 11511
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 11339
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 86617
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 1465007093 (1.36 GB)
telemt_user_octets_to_client{user="hello"} 33922019091 (31.59 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 72180.2 (20h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 486063
telemt_connections_bad_total 57810
telemt_handshake_timeouts_total 3983
telemt_upstream_connect_attempt_total 15575
telemt_upstream_connect_success_total 15484
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 15575
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7967
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 14
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 13140
telemt_me_reconnect_success_total 11835
telemt_me_reader_eof_total 12575
telemt_me_idle_close_by_peer_total 12575
telemt_me_route_drop_no_conn_total 312312
telemt_me_route_drop_channel_closed_total 76
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 447812
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 317
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 231
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 12001
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 11808
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 406395
telemt_user_connections_current{user="hello"} 533
telemt_user_octets_from_client{user="hello"} 10505065536 (9.78 GB)
telemt_user_octets_to_client{user="hello"} 219823729228 (204.73 GB)
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 63
```