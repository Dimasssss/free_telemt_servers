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

# Server Metrics 2026-03-14 05:56:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 166987.9 (46h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 642920
telemt_connections_bad_total 32303
telemt_handshake_timeouts_total 12999
telemt_upstream_connect_attempt_total 42577
telemt_upstream_connect_success_total 42361
telemt_upstream_connect_fail_total 216
telemt_upstream_connect_attempts_per_request{bucket="1"} 42577
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22875
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 216
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5577
telemt_me_reconnect_attempts_total 38342
telemt_me_reconnect_success_total 33653
telemt_me_reader_eof_total 35986
telemt_me_idle_close_by_peer_total 35985
telemt_me_route_drop_no_conn_total 210159
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 545184
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1946
telemt_desync_full_logged_total 666
telemt_desync_suppressed_total 1280
telemt_desync_frames_bucket_total{bucket="1_2"} 420
telemt_desync_frames_bucket_total{bucket="3_10"} 713
telemt_desync_frames_bucket_total{bucket="gt_10"} 813
telemt_pool_swap_total 154
telemt_me_writer_removed_unexpected_total 34166
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 33633
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 513
telemt_user_connections_total{user="hello"} 545069
telemt_user_connections_current{user="hello"} 285
telemt_user_octets_from_client{user="hello"} 15986507866 (14.89 GB)
telemt_user_octets_to_client{user="hello"} 264618014732 (246.44 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 166881.6 (46h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 324495
telemt_connections_bad_total 2289
telemt_handshake_timeouts_total 2370
telemt_upstream_connect_attempt_total 149050
telemt_upstream_connect_success_total 147817
telemt_upstream_connect_fail_total 1233
telemt_upstream_connect_attempts_per_request{bucket="1"} 149050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35943
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2420
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1233
telemt_me_keepalive_timeout_total 3909
telemt_me_reconnect_attempts_total 174152
telemt_me_reconnect_success_total 36188
telemt_me_reader_eof_total 41446
telemt_me_idle_close_by_peer_total 41446
telemt_me_route_drop_no_conn_total 104784
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 204285
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 42
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
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 40836
telemt_me_refill_failed_total 4305
telemt_me_writer_restored_same_endpoint_total 36171
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4648
telemt_user_connections_total{user="hello"} 307391
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 3186842199 (2.97 GB)
telemt_user_octets_to_client{user="hello"} 100163753859 (93.28 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 166845.1 (46h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 377602
telemt_connections_bad_total 2965
telemt_handshake_timeouts_total 34925
telemt_upstream_connect_attempt_total 44182
telemt_upstream_connect_success_total 44173
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 44182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23942
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3418
telemt_me_reconnect_attempts_total 37096
telemt_me_reconnect_success_total 35812
telemt_me_reader_eof_total 38511
telemt_me_idle_close_by_peer_total 38511
telemt_me_route_drop_no_conn_total 135858
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 326626
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
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
telemt_pool_swap_total 158
telemt_me_writer_removed_unexpected_total 36245
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 35791
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 433
telemt_user_connections_total{user="hello"} 326404
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 13345044184 (12.43 GB)
telemt_user_octets_to_client{user="hello"} 129740959008 (120.83 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 166820.1 (46h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 478871
telemt_connections_bad_total 15653
telemt_handshake_timeouts_total 4479
telemt_upstream_connect_attempt_total 74260
telemt_upstream_connect_success_total 63704
telemt_upstream_connect_fail_total 10556
telemt_upstream_connect_attempts_per_request{bucket="1"} 74260
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37757
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25602
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 336
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10556
telemt_me_keepalive_timeout_total 5316
telemt_me_reconnect_attempts_total 142407
telemt_me_reconnect_success_total 36352
telemt_me_reader_eof_total 40819
telemt_me_idle_close_by_peer_total 40811
telemt_me_route_drop_no_conn_total 172385
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 407034
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1730
telemt_desync_full_logged_total 512
telemt_desync_suppressed_total 1218
telemt_desync_frames_bucket_total{bucket="1_2"} 408
telemt_desync_frames_bucket_total{bucket="3_10"} 655
telemt_desync_frames_bucket_total{bucket="gt_10"} 667
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 40079
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 36342
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3727
telemt_user_connections_total{user="hello"} 425875
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 9249475899 (8.61 GB)
telemt_user_octets_to_client{user="hello"} 168528174488 (156.95 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 116992.3 (32h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 191584
telemt_connections_bad_total 28387
telemt_handshake_timeouts_total 1661
telemt_upstream_connect_attempt_total 41644
telemt_upstream_connect_success_total 41255
telemt_upstream_connect_fail_total 389
telemt_upstream_connect_attempts_per_request{bucket="1"} 41644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20666
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20454
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 389
telemt_me_keepalive_timeout_total 2418
telemt_me_reconnect_attempts_total 43987
telemt_me_reconnect_success_total 30562
telemt_me_reader_eof_total 32720
telemt_me_idle_close_by_peer_total 32720
telemt_me_route_drop_no_conn_total 56652
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 151431
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 623
telemt_desync_full_logged_total 147
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 31260
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 30544
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 698
telemt_user_connections_total{user="hello"} 156180
telemt_user_connections_current{user="hello"} 74
telemt_user_octets_from_client{user="hello"} 2328747913 (2.17 GB)
telemt_user_octets_to_client{user="hello"} 70989907611 (66.11 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 166776.3 (46h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 952227
telemt_connections_bad_total 35987
telemt_handshake_timeouts_total 25890
telemt_upstream_connect_attempt_total 34649
telemt_upstream_connect_success_total 34462
telemt_upstream_connect_fail_total 187
telemt_upstream_connect_attempts_per_request{bucket="1"} 34649
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16190
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18231
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 187
telemt_me_keepalive_timeout_total 4613
telemt_me_reconnect_attempts_total 30876
telemt_me_reconnect_success_total 26200
telemt_me_reader_eof_total 28125
telemt_me_idle_close_by_peer_total 28122
telemt_me_route_drop_no_conn_total 448963
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 882408
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 760
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 510
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 158
telemt_me_writer_removed_unexpected_total 26679
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 26193
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 479
telemt_user_connections_total{user="hello"} 855061
telemt_user_connections_current{user="hello"} 398
telemt_user_octets_from_client{user="hello"} 14821742812 (13.80 GB)
telemt_user_octets_to_client{user="hello"} 436316561836 (406.35 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 61
```