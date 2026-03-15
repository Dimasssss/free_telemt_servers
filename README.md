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

# Server Metrics 2026-03-15 14:22:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 58093.1 (16h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 261499
telemt_connections_bad_total 2416
telemt_handshake_timeouts_total 6228
telemt_upstream_connect_attempt_total 14717
telemt_upstream_connect_success_total 14641
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 14717
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8138
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 15108
telemt_me_reconnect_success_total 11729
telemt_me_reader_eof_total 12506
telemt_me_idle_close_by_peer_total 12506
telemt_me_route_drop_no_conn_total 438633
telemt_me_route_drop_channel_closed_total 72
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 303695
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1700
telemt_desync_full_logged_total 674
telemt_desync_suppressed_total 1026
telemt_desync_frames_bucket_total{bucket="1_2"} 305
telemt_desync_frames_bucket_total{bucket="3_10"} 661
telemt_desync_frames_bucket_total{bucket="gt_10"} 734
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 11953
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 11698
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 224
telemt_user_connections_total{user="hello"} 242801
telemt_user_connections_current{user="hello"} 394
telemt_user_octets_from_client{user="hello"} 5341042260 (4.97 GB)
telemt_user_octets_to_client{user="hello"} 211791111832 (197.25 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 58100.6 (16h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96432
telemt_connections_bad_total 2782
telemt_handshake_timeouts_total 9400
telemt_upstream_connect_attempt_total 16005
telemt_upstream_connect_success_total 16005
telemt_upstream_connect_attempts_per_request{bucket="1"} 16005
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8986
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 15412
telemt_me_reconnect_success_total 13062
telemt_me_reader_eof_total 13978
telemt_me_idle_close_by_peer_total 13978
telemt_me_route_drop_no_conn_total 41072
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81315
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 13288
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 13046
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 226
telemt_user_connections_total{user="hello"} 81306
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 1610341088 (1.50 GB)
telemt_user_octets_to_client{user="hello"} 39162439260 (36.47 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 58092.9 (16h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105345
telemt_connections_bad_total 1645
telemt_handshake_timeouts_total 2776
telemt_upstream_connect_attempt_total 17280
telemt_upstream_connect_success_total 17272
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 17280
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7443
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9796
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 20315
telemt_me_reconnect_success_total 14320
telemt_me_reader_eof_total 15358
telemt_me_idle_close_by_peer_total 15358
telemt_me_route_drop_no_conn_total 39215
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 90457
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 54
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 14639
telemt_me_refill_failed_total 185
telemt_me_writer_restored_same_endpoint_total 14312
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 319
telemt_user_connections_total{user="hello"} 90362
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 10142217208 (9.45 GB)
telemt_user_octets_to_client{user="hello"} 53176645640 (49.52 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 58092.7 (16h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138563
telemt_connections_bad_total 780
telemt_handshake_timeouts_total 914
telemt_upstream_connect_attempt_total 13837
telemt_upstream_connect_success_total 13833
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 13837
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7147
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 10986
telemt_me_reconnect_success_total 10920
telemt_me_reader_eof_total 11622
telemt_me_idle_close_by_peer_total 11622
telemt_me_route_drop_no_conn_total 53868
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 126492
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 431
telemt_desync_full_logged_total 135
telemt_desync_suppressed_total 296
telemt_desync_frames_bucket_total{bucket="1_2"} 90
telemt_desync_frames_bucket_total{bucket="3_10"} 191
telemt_desync_frames_bucket_total{bucket="gt_10"} 150
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 11045
telemt_me_writer_restored_same_endpoint_total 10909
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 126408
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 2374600704 (2.21 GB)
telemt_user_octets_to_client{user="hello"} 62944960080 (58.62 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 33164.2 (9h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79879
telemt_connections_bad_total 21233
telemt_handshake_timeouts_total 1416
telemt_upstream_connect_attempt_total 10507
telemt_upstream_connect_success_total 10441
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 10507
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4747
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5652
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 103032
telemt_me_reconnect_success_total 8606
telemt_me_reader_eof_total 8992
telemt_me_idle_close_by_peer_total 8992
telemt_me_route_drop_no_conn_total 26979
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55432
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 151
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 119
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 8621
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 8502
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 55569
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 839744185 (800.84 MB)
telemt_user_octets_to_client{user="hello"} 22759048683 (21.20 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 58092.1 (16h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 348902
telemt_connections_bad_total 48423
telemt_handshake_timeouts_total 2871
telemt_upstream_connect_attempt_total 12496
telemt_upstream_connect_success_total 12421
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 12496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6226
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 10776
telemt_me_reconnect_success_total 9490
telemt_me_reader_eof_total 10107
telemt_me_idle_close_by_peer_total 10107
telemt_me_route_drop_no_conn_total 161120
telemt_me_route_drop_channel_closed_total 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 287345
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 301
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 222
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 9618
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 9463
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 285202
telemt_user_connections_current{user="hello"} 593
telemt_user_octets_from_client{user="hello"} 6999973064 (6.52 GB)
telemt_user_octets_to_client{user="hello"} 140274178852 (130.64 GB)
telemt_user_unique_ips_current{user="hello"} 218
telemt_user_unique_ips_recent_window{user="hello"} 75
```