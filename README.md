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

# Server Metrics 2026-03-15 10:38:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 44618.1 (12h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 186013
telemt_connections_bad_total 1341
telemt_handshake_timeouts_total 4231
telemt_upstream_connect_attempt_total 11199
telemt_upstream_connect_success_total 11140
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 11199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6155
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 11280
telemt_me_reconnect_success_total 8908
telemt_me_reader_eof_total 9521
telemt_me_idle_close_by_peer_total 9521
telemt_me_route_drop_no_conn_total 412929
telemt_me_route_drop_channel_closed_total 61
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 234413
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1396
telemt_desync_full_logged_total 553
telemt_desync_suppressed_total 843
telemt_desync_frames_bucket_total{bucket="1_2"} 225
telemt_desync_frames_bucket_total{bucket="3_10"} 557
telemt_desync_frames_bucket_total{bucket="gt_10"} 614
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 9063
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 8877
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 173672
telemt_user_connections_current{user="hello"} 397
telemt_user_octets_from_client{user="hello"} 2787618016 (2.60 GB)
telemt_user_octets_to_client{user="hello"} 179429191788 (167.11 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 44625.2 (12h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59993
telemt_connections_bad_total 2309
telemt_handshake_timeouts_total 3054
telemt_upstream_connect_attempt_total 12002
telemt_upstream_connect_success_total 12002
telemt_upstream_connect_attempts_per_request{bucket="1"} 12002
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6760
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 12072
telemt_me_reconnect_success_total 9750
telemt_me_reader_eof_total 10466
telemt_me_idle_close_by_peer_total 10466
telemt_me_route_drop_no_conn_total 28350
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52708
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 9928
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 9734
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 52706
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 1026270520 (978.73 MB)
telemt_user_octets_to_client{user="hello"} 22834086976 (21.27 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 44618.1 (12h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67886
telemt_connections_bad_total 645
telemt_handshake_timeouts_total 2437
telemt_upstream_connect_attempt_total 12423
telemt_upstream_connect_success_total 12422
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5299
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7112
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 11372
telemt_me_reconnect_success_total 10173
telemt_me_reader_eof_total 10937
telemt_me_idle_close_by_peer_total 10937
telemt_me_route_drop_no_conn_total 25454
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62131
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 30
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 10301
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 10169
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 62055
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 9311403744 (8.67 GB)
telemt_user_octets_to_client{user="hello"} 37862499824 (35.26 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 44617.5 (12h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88076
telemt_connections_bad_total 207
telemt_handshake_timeouts_total 591
telemt_upstream_connect_attempt_total 10587
telemt_upstream_connect_success_total 10586
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10587
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5495
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 8400
telemt_me_reconnect_success_total 8359
telemt_me_reader_eof_total 8917
telemt_me_idle_close_by_peer_total 8917
telemt_me_route_drop_no_conn_total 36506
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80325
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 171
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 117
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 69
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 8446
telemt_me_writer_restored_same_endpoint_total 8348
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 80255
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 1595024824 (1.49 GB)
telemt_user_octets_to_client{user="hello"} 49579314432 (46.17 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 19689.0 (5h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33217
telemt_connections_bad_total 3678
telemt_handshake_timeouts_total 495
telemt_upstream_connect_attempt_total 6588
telemt_upstream_connect_success_total 6537
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 6588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2927
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3590
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_reconnect_attempts_total 99790
telemt_me_reconnect_success_total 5381
telemt_me_reader_eof_total 5566
telemt_me_idle_close_by_peer_total 5566
telemt_me_route_drop_no_conn_total 11175
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 28231
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 40
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 33
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 5353
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 5277
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 28371
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 435702905 (415.52 MB)
telemt_user_octets_to_client{user="hello"} 12884650823 (12.00 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 44616.9 (12h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 238932
telemt_connections_bad_total 44404
telemt_handshake_timeouts_total 1500
telemt_upstream_connect_attempt_total 9497
telemt_upstream_connect_success_total 9440
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 9497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4670
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 7249
telemt_me_reconnect_success_total 7206
telemt_me_reader_eof_total 7684
telemt_me_idle_close_by_peer_total 7684
telemt_me_route_drop_no_conn_total 104935
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 186675
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 80
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 39
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 7261
telemt_me_writer_restored_same_endpoint_total 7179
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 185044
telemt_user_connections_current{user="hello"} 519
telemt_user_octets_from_client{user="hello"} 4470667736 (4.16 GB)
telemt_user_octets_to_client{user="hello"} 94394865732 (87.91 GB)
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 75
```