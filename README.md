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

# Server Metrics 2026-03-13 10:07:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 95624.6 (26h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 378147
telemt_connections_bad_total 3191
telemt_handshake_timeouts_total 7975
telemt_upstream_connect_attempt_total 24192
telemt_upstream_connect_success_total 24080
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 24192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10847
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13185
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1750
telemt_me_reconnect_attempts_total 22781
telemt_me_reconnect_success_total 19262
telemt_me_reader_eof_total 20581
telemt_me_idle_close_by_peer_total 20580
telemt_me_route_drop_no_conn_total 118310
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 325111
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1049
telemt_desync_full_logged_total 390
telemt_desync_suppressed_total 659
telemt_desync_frames_bucket_total{bucket="1_2"} 216
telemt_desync_frames_bucket_total{bucket="3_10"} 383
telemt_desync_frames_bucket_total{bucket="gt_10"} 450
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 19573
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 19246
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 311
telemt_user_connections_total{user="hello"} 324815
telemt_user_connections_current{user="hello"} 371
telemt_user_octets_from_client{user="hello"} 5720893712 (5.33 GB)
telemt_user_octets_to_client{user="hello"} 142049744100 (132.29 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 95518.0 (26h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173461
telemt_connections_bad_total 1561
telemt_handshake_timeouts_total 1314
telemt_upstream_connect_attempt_total 47199
telemt_upstream_connect_success_total 46549
telemt_upstream_connect_fail_total 650
telemt_upstream_connect_attempts_per_request{bucket="1"} 47199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19219
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 517
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 650
telemt_me_keepalive_timeout_total 734
telemt_me_reconnect_attempts_total 82918
telemt_me_reconnect_success_total 25269
telemt_me_reader_eof_total 27818
telemt_me_idle_close_by_peer_total 27818
telemt_me_route_drop_no_conn_total 73961
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 147012
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 20
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
telemt_me_writer_removed_unexpected_total 27284
telemt_me_refill_failed_total 1799
telemt_me_writer_restored_same_endpoint_total 25254
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2015
telemt_user_connections_total{user="hello"} 163292
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 1703567392 (1.59 GB)
telemt_user_octets_to_client{user="hello"} 53518087423 (49.84 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 95481.6 (26h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211303
telemt_connections_bad_total 2027
telemt_handshake_timeouts_total 4218
telemt_upstream_connect_attempt_total 25769
telemt_upstream_connect_success_total 25766
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 25769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11856
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13885
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 721
telemt_me_reconnect_attempts_total 22143
telemt_me_reconnect_success_total 20952
telemt_me_reader_eof_total 22463
telemt_me_idle_close_by_peer_total 22463
telemt_me_route_drop_no_conn_total 79462
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 197340
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 63
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 21182
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 20932
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 230
telemt_user_connections_total{user="hello"} 197261
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 9164800704 (8.54 GB)
telemt_user_octets_to_client{user="hello"} 81420795900 (75.83 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 95457.5 (26h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 299016
telemt_connections_bad_total 13673
telemt_handshake_timeouts_total 2165
telemt_upstream_connect_attempt_total 38707
telemt_upstream_connect_success_total 28690
telemt_upstream_connect_fail_total 10017
telemt_upstream_connect_attempts_per_request{bucket="1"} 38707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14379
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14113
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10017
telemt_me_keepalive_timeout_total 3433
telemt_me_reconnect_attempts_total 80361
telemt_me_reconnect_success_total 21068
telemt_me_reader_eof_total 23565
telemt_me_idle_close_by_peer_total 23558
telemt_me_route_drop_no_conn_total 108025
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 256389
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 965
telemt_desync_full_logged_total 284
telemt_desync_suppressed_total 681
telemt_desync_frames_bucket_total{bucket="1_2"} 240
telemt_desync_frames_bucket_total{bucket="3_10"} 355
telemt_desync_frames_bucket_total{bucket="gt_10"} 370
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 23187
telemt_me_refill_failed_total 1848
telemt_me_writer_restored_same_endpoint_total 21058
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2119
telemt_user_connections_total{user="hello"} 259113
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 5628803262 (5.24 GB)
telemt_user_octets_to_client{user="hello"} 97012236225 (90.35 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 45628.9 (12h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60960
telemt_connections_bad_total 9142
telemt_handshake_timeouts_total 492
telemt_upstream_connect_attempt_total 15720
telemt_upstream_connect_success_total 15569
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 15720
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6822
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8694
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_timeout_total 397
telemt_me_reconnect_attempts_total 15514
telemt_me_reconnect_success_total 13286
telemt_me_reader_eof_total 14146
telemt_me_idle_close_by_peer_total 14146
telemt_me_route_drop_no_conn_total 18885
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49504
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 76
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 63
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 13473
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 13268
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 49499
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 450322620 (429.46 MB)
telemt_user_octets_to_client{user="hello"} 13416471132 (12.50 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 95414.0 (26h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 520802
telemt_connections_bad_total 14504
telemt_handshake_timeouts_total 7013
telemt_upstream_connect_attempt_total 20307
telemt_upstream_connect_success_total 20201
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 20307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10713
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 1575
telemt_me_reconnect_attempts_total 19126
telemt_me_reconnect_success_total 15473
telemt_me_reader_eof_total 16595
telemt_me_idle_close_by_peer_total 16592
telemt_me_route_drop_no_conn_total 268627
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 507857
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 408
telemt_desync_full_logged_total 158
telemt_desync_suppressed_total 250
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 148
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 15788
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 15466
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 315
telemt_user_connections_total{user="hello"} 480938
telemt_user_connections_current{user="hello"} 455
telemt_user_octets_from_client{user="hello"} 8620873576 (8.03 GB)
telemt_user_octets_to_client{user="hello"} 270984187096 (252.37 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 66
```