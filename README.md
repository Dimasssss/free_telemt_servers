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

# Server Metrics 2026-03-15 06:59:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 31473.6 (8h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93171
telemt_connections_bad_total 524
telemt_handshake_timeouts_total 1973
telemt_upstream_connect_attempt_total 7608
telemt_upstream_connect_success_total 7563
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 7608
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4126
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 6031
telemt_me_reconnect_success_total 6010
telemt_me_reader_eof_total 6437
telemt_me_idle_close_by_peer_total 6437
telemt_me_route_drop_no_conn_total 110540
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100737
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 775
telemt_desync_full_logged_total 339
telemt_desync_suppressed_total 436
telemt_desync_frames_bucket_total{bucket="1_2"} 139
telemt_desync_frames_bucket_total{bucket="3_10"} 325
telemt_desync_frames_bucket_total{bucket="gt_10"} 311
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 6060
telemt_me_writer_restored_same_endpoint_total 5979
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 86956
telemt_user_connections_current{user="hello"} 335
telemt_user_octets_from_client{user="hello"} 1145848336 (1.07 GB)
telemt_user_octets_to_client{user="hello"} 58249004544 (54.25 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 31481.0 (8h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30728
telemt_connections_bad_total 153
telemt_handshake_timeouts_total 122
telemt_upstream_connect_attempt_total 8414
telemt_upstream_connect_success_total 8414
telemt_upstream_connect_attempts_per_request{bucket="1"} 8414
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4707
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6877
telemt_me_reconnect_success_total 6849
telemt_me_reader_eof_total 7361
telemt_me_idle_close_by_peer_total 7361
telemt_me_route_drop_no_conn_total 15897
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29245
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 6915
telemt_me_writer_restored_same_endpoint_total 6833
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 29248
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 762580896 (727.25 MB)
telemt_user_octets_to_client{user="hello"} 11196131936 (10.43 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 31473.7 (8h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39241
telemt_connections_bad_total 457
telemt_handshake_timeouts_total 1799
telemt_upstream_connect_attempt_total 8339
telemt_upstream_connect_success_total 8338
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8339
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3669
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4662
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 6805
telemt_me_reconnect_success_total 6775
telemt_me_reader_eof_total 7324
telemt_me_idle_close_by_peer_total 7324
telemt_me_route_drop_no_conn_total 13429
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35185
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 6835
telemt_me_writer_restored_same_endpoint_total 6771
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 35123
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 8810901256 (8.21 GB)
telemt_user_octets_to_client{user="hello"} 19289260952 (17.96 GB)
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 31473.3 (8h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44253
telemt_connections_bad_total 131
telemt_handshake_timeouts_total 288
telemt_upstream_connect_attempt_total 7338
telemt_upstream_connect_success_total 7337
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3427
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3889
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 5810
telemt_me_reconnect_success_total 5787
telemt_me_reader_eof_total 6202
telemt_me_idle_close_by_peer_total 6202
telemt_me_route_drop_no_conn_total 19171
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 39867
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 81
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 59
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 5849
telemt_me_writer_restored_same_endpoint_total 5776
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 39786
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 745182588 (710.66 MB)
telemt_user_octets_to_client{user="hello"} 25483808444 (23.73 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 6544.9 (1h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9200
telemt_connections_bad_total 1236
telemt_handshake_timeouts_total 155
telemt_upstream_connect_attempt_total 2619
telemt_upstream_connect_success_total 2585
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 2619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1125
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1448
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_reconnect_attempts_total 96455
telemt_me_reconnect_success_total 2061
telemt_me_reader_eof_total 2068
telemt_me_idle_close_by_peer_total 2068
telemt_me_route_drop_no_conn_total 2530
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7484
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1995
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 1957
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 7629
telemt_user_connections_current{user="hello"} 46
telemt_user_octets_from_client{user="hello"} 47998353 (45.77 MB)
telemt_user_octets_to_client{user="hello"} 3543573399 (3.30 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 31472.6 (8h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115289
telemt_connections_bad_total 7034
telemt_handshake_timeouts_total 508
telemt_upstream_connect_attempt_total 6842
telemt_upstream_connect_success_total 6803
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 6842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3383
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_reconnect_attempts_total 5267
telemt_me_reconnect_success_total 5243
telemt_me_reader_eof_total 5582
telemt_me_idle_close_by_peer_total 5582
telemt_me_route_drop_no_conn_total 59239
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 104550
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 25
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 5267
telemt_me_writer_restored_same_endpoint_total 5216
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 103108
telemt_user_connections_current{user="hello"} 453
telemt_user_octets_from_client{user="hello"} 2695590992 (2.51 GB)
telemt_user_octets_to_client{user="hello"} 53191289976 (49.54 GB)
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 60
```