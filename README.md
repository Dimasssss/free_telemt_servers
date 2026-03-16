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

# Server Metrics 2026-03-16 15:54:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 8204.0 (2h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90308
telemt_connections_bad_total 581
telemt_handshake_timeouts_total 2815
telemt_upstream_connect_attempt_total 1811
telemt_upstream_connect_success_total 1806
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 871
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 934
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1349
telemt_me_reconnect_success_total 1338
telemt_me_reader_eof_total 1348
telemt_me_idle_close_by_peer_total 1348
telemt_me_route_drop_no_conn_total 26005
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 83695
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 407
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 327
telemt_desync_frames_bucket_total{bucket="1_2"} 179
telemt_desync_frames_bucket_total{bucket="3_10"} 152
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1337
telemt_me_writer_restored_same_endpoint_total 1336
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 83620
telemt_user_connections_current{user="hello"} 599
telemt_user_octets_from_client{user="hello"} 1670339944 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 48206279976 (44.90 GB)
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 2982.8 (0h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21915
telemt_connections_bad_total 23
telemt_handshake_timeouts_total 418
telemt_upstream_connect_attempt_total 585
telemt_upstream_connect_success_total 578
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 584
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 316
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 383
telemt_me_reconnect_success_total 374
telemt_me_reader_eof_total 365
telemt_me_idle_close_by_peer_total 365
telemt_me_route_drop_no_conn_total 12575
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20749
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 380
telemt_me_writer_restored_same_endpoint_total 369
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 343
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 20724
telemt_user_connections_current{user="hello"} 384
telemt_user_octets_from_client{user="hello"} 157321588 (150.03 MB)
telemt_user_octets_to_client{user="hello"} 5244064444 (4.88 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 8317.0 (2h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36027
telemt_connections_bad_total 31
telemt_handshake_timeouts_total 606
telemt_upstream_connect_attempt_total 2595
telemt_upstream_connect_success_total 2557
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 2595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1037
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_reconnect_attempts_total 37762
telemt_me_reconnect_success_total 1098
telemt_me_reader_eof_total 1325
telemt_me_idle_close_by_peer_total 1325
telemt_me_route_drop_no_conn_total 11410
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32223
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 36
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 21
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_me_writer_removed_unexpected_total 1349
telemt_me_refill_failed_total 1145
telemt_me_writer_restored_same_endpoint_total 1054
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 251
telemt_user_connections_total{user="hello"} 33172
telemt_user_connections_current{user="hello"} 243
telemt_user_octets_from_client{user="hello"} 352581378 (336.25 MB)
telemt_user_octets_to_client{user="hello"} 5280099186 (4.92 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 8453.3 (2h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65064
telemt_connections_bad_total 135
telemt_handshake_timeouts_total 903
telemt_upstream_connect_attempt_total 1728
telemt_upstream_connect_success_total 1719
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 840
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 860
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 7540
telemt_me_reconnect_success_total 1211
telemt_me_reader_eof_total 1397
telemt_me_idle_close_by_peer_total 1397
telemt_me_route_drop_no_conn_total 22075
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61744
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 329
telemt_desync_full_logged_total 91
telemt_desync_suppressed_total 238
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 140
telemt_desync_frames_bucket_total{bucket="gt_10"} 136
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1414
telemt_me_refill_failed_total 197
telemt_me_writer_restored_same_endpoint_total 1207
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 203
telemt_user_connections_total{user="hello"} 61723
telemt_user_connections_current{user="hello"} 428
telemt_user_octets_from_client{user="hello"} 1009528060 (962.76 MB)
telemt_user_octets_to_client{user="hello"} 14748648032 (13.74 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 5913.9 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32343
telemt_connections_bad_total 11598
telemt_handshake_timeouts_total 242
telemt_upstream_connect_attempt_total 1492
telemt_upstream_connect_success_total 1472
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 1492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 550
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 873
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 1786
telemt_me_reconnect_success_total 1132
telemt_me_reader_eof_total 1169
telemt_me_idle_close_by_peer_total 1169
telemt_me_route_drop_no_conn_total 7831
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19480
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 12
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1167
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 1132
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 19459
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 418387208 (399.01 MB)
telemt_user_octets_to_client{user="hello"} 6483848176 (6.04 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 8021.0 (2h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92984
telemt_connections_bad_total 1192
telemt_handshake_timeouts_total 1886
telemt_upstream_connect_attempt_total 1647
telemt_upstream_connect_success_total 1647
telemt_upstream_connect_attempts_per_request{bucket="1"} 1647
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 845
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 3588
telemt_me_reconnect_success_total 1209
telemt_me_reader_eof_total 1292
telemt_me_idle_close_by_peer_total 1292
telemt_me_route_drop_no_conn_total 42950
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 86989
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1291
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 1205
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 86722
telemt_user_connections_current{user="hello"} 760
telemt_user_octets_from_client{user="hello"} 1856463496 (1.73 GB)
telemt_user_octets_to_client{user="hello"} 27346996304 (25.47 GB)
telemt_user_unique_ips_current{user="hello"} 268
telemt_user_unique_ips_recent_window{user="hello"} 116
```