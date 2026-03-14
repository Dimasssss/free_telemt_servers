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

# Server Metrics 2026-03-14 16:12:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 10592.0 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61878
telemt_connections_bad_total 12271
telemt_handshake_timeouts_total 292
telemt_upstream_connect_attempt_total 2708
telemt_upstream_connect_success_total 2706
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1293
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1342
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 2154
telemt_me_reconnect_success_total 2128
telemt_me_reader_eof_total 2225
telemt_me_idle_close_by_peer_total 2225
telemt_me_route_drop_no_conn_total 22789
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47810
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 139
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 64
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2174
telemt_me_writer_restored_same_endpoint_total 2110
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 47743
telemt_user_connections_current{user="hello"} 367
telemt_user_octets_from_client{user="hello"} 792447044 (755.74 MB)
telemt_user_octets_to_client{user="hello"} 16894131276 (15.73 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 10590.1 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24677
telemt_connections_bad_total 390
telemt_handshake_timeouts_total 539
telemt_upstream_connect_attempt_total 2997
telemt_upstream_connect_success_total 2968
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 2997
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1208
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1725
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 48
telemt_me_reconnect_attempts_total 4958
telemt_me_reconnect_success_total 2394
telemt_me_reader_eof_total 2536
telemt_me_idle_close_by_peer_total 2536
telemt_me_route_drop_no_conn_total 12822
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22936
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2511
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 2389
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 22920
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 298580804 (284.75 MB)
telemt_user_octets_to_client{user="hello"} 9512175408 (8.86 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 10594.0 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24580
telemt_connections_bad_total 227
telemt_handshake_timeouts_total 1294
telemt_upstream_connect_attempt_total 4343
telemt_upstream_connect_success_total 4302
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 4343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2163
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 73
telemt_me_reconnect_attempts_total 97294
telemt_me_reconnect_success_total 3412
telemt_me_reader_eof_total 3573
telemt_me_idle_close_by_peer_total 3573
telemt_me_route_drop_no_conn_total 9397
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21466
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 3539
telemt_me_refill_failed_total 3045
telemt_me_writer_restored_same_endpoint_total 3374
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 21756
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 603178573 (575.24 MB)
telemt_user_octets_to_client{user="hello"} 10243982186 (9.54 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 10599.1 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33582
telemt_connections_bad_total 101
telemt_handshake_timeouts_total 224
telemt_upstream_connect_attempt_total 3023
telemt_upstream_connect_success_total 3007
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3023
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1618
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 66
telemt_me_reconnect_attempts_total 2451
telemt_me_reconnect_success_total 2435
telemt_me_reader_eof_total 2502
telemt_me_idle_close_by_peer_total 2502
telemt_me_route_drop_no_conn_total 15748
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31980
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 337
telemt_desync_full_logged_total 91
telemt_desync_suppressed_total 246
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 137
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2455
telemt_me_writer_restored_same_endpoint_total 2433
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 31862
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 364136824 (347.27 MB)
telemt_user_octets_to_client{user="hello"} 11623674208 (10.83 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 10592.3 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23531
telemt_connections_bad_total 2124
telemt_handshake_timeouts_total 902
telemt_upstream_connect_attempt_total 2426
telemt_upstream_connect_success_total 2393
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 2426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1368
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 8332
telemt_me_reconnect_success_total 1817
telemt_me_reader_eof_total 2029
telemt_me_idle_close_by_peer_total 2029
telemt_me_route_drop_no_conn_total 8282
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19396
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 96
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 85
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2026
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 1813
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 19391
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 178121896 (169.87 MB)
telemt_user_octets_to_client{user="hello"} 5323214272 (4.96 GB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 10591.8 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82024
telemt_connections_bad_total 235
telemt_handshake_timeouts_total 755
telemt_upstream_connect_attempt_total 2317
telemt_upstream_connect_success_total 2272
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 2317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1137
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1134
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 48
telemt_me_reconnect_attempts_total 5342
telemt_me_reconnect_success_total 1692
telemt_me_reader_eof_total 1829
telemt_me_idle_close_by_peer_total 1829
telemt_me_route_drop_no_conn_total 42045
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76207
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 20
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1822
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 1688
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 76102
telemt_user_connections_current{user="hello"} 546
telemt_user_octets_from_client{user="hello"} 1267670708 (1.18 GB)
telemt_user_octets_to_client{user="hello"} 31084735368 (28.95 GB)
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 67
```