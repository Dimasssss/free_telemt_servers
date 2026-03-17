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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-17 09:27:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 52950.0 (14h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 411852
telemt_connections_bad_total 3650
telemt_handshake_timeouts_total 12106
telemt_upstream_connect_attempt_total 13522
telemt_upstream_connect_success_total 13092
telemt_upstream_connect_fail_total 430
telemt_upstream_connect_attempts_per_request{bucket="1"} 13522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5947
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 430
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 9698
telemt_me_reconnect_success_total 8176
telemt_me_reader_eof_total 8692
telemt_me_idle_close_by_peer_total 8691
telemt_me_route_drop_no_conn_total 129674
telemt_me_route_drop_channel_closed_total 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 370735
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2896
telemt_desync_full_logged_total 800
telemt_desync_suppressed_total 2096
telemt_desync_frames_bucket_total{bucket="1_2"} 686
telemt_desync_frames_bucket_total{bucket="3_10"} 1319
telemt_desync_frames_bucket_total{bucket="gt_10"} 891
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 8343
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 8154
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 372724
telemt_user_connections_current{user="hello"} 892
telemt_user_octets_from_client{user="hello"} 5325461855 (4.96 GB)
telemt_user_octets_to_client{user="hello"} 149032887851 (138.80 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 316
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 53202.1 (14h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 223598
telemt_connections_bad_total 2433
telemt_handshake_timeouts_total 12756
telemt_upstream_connect_attempt_total 14051
telemt_upstream_connect_success_total 13861
telemt_upstream_connect_fail_total 190
telemt_upstream_connect_attempts_per_request{bucket="1"} 14051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7762
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 190
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 17210
telemt_me_reconnect_success_total 11222
telemt_me_reader_eof_total 11971
telemt_me_idle_close_by_peer_total 11971
telemt_me_route_drop_no_conn_total 82016
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 197470
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 534
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 340
telemt_desync_frames_bucket_total{bucket="1_2"} 161
telemt_desync_frames_bucket_total{bucket="3_10"} 230
telemt_desync_frames_bucket_total{bucket="gt_10"} 143
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 11522
telemt_me_refill_failed_total 186
telemt_me_writer_restored_same_endpoint_total 11206
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 300
telemt_user_connections_total{user="hello"} 197473
telemt_user_connections_current{user="hello"} 477
telemt_user_octets_from_client{user="hello"} 2372811524 (2.21 GB)
telemt_user_octets_to_client{user="hello"} 77488701572 (72.17 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 52977.7 (14h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138024
telemt_connections_bad_total 7575
telemt_handshake_timeouts_total 9285
telemt_upstream_connect_attempt_total 14138
telemt_upstream_connect_success_total 14065
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 14138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7787
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 12374
telemt_me_reconnect_success_total 11408
telemt_me_reader_eof_total 12181
telemt_me_idle_close_by_peer_total 12181
telemt_me_route_drop_no_conn_total 42083
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111868
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 335
telemt_desync_full_logged_total 88
telemt_desync_suppressed_total 247
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 140
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 11585
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 11397
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 177
telemt_user_connections_total{user="hello"} 111790
telemt_user_connections_current{user="hello"} 319
telemt_user_octets_from_client{user="hello"} 7509863380 (6.99 GB)
telemt_user_octets_to_client{user="hello"} 34971653668 (32.57 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 53036.9 (14h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 301664
telemt_connections_bad_total 6184
telemt_handshake_timeouts_total 10756
telemt_upstream_connect_attempt_total 12022
telemt_upstream_connect_success_total 11913
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 12022
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6227
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 10301
telemt_me_reconnect_success_total 9222
telemt_me_reader_eof_total 9811
telemt_me_idle_close_by_peer_total 9811
telemt_me_route_drop_no_conn_total 83183
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 241299
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 501
telemt_desync_full_logged_total 189
telemt_desync_suppressed_total 312
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 216
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 9396
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 9214
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 174
telemt_user_connections_total{user="hello"} 241253
telemt_user_connections_current{user="hello"} 692
telemt_user_octets_from_client{user="hello"} 2592290178 (2.41 GB)
telemt_user_octets_to_client{user="hello"} 98091952865 (91.36 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 53008.8 (14h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169812
telemt_connections_bad_total 46211
telemt_handshake_timeouts_total 2759
telemt_upstream_connect_attempt_total 16166
telemt_upstream_connect_success_total 15955
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 16166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8622
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 202
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_reconnect_attempts_total 20319
telemt_me_reconnect_success_total 13207
telemt_me_reader_eof_total 13995
telemt_me_idle_close_by_peer_total 13995
telemt_me_route_drop_no_conn_total 44287
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 115649
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 365
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 271
telemt_desync_frames_bucket_total{bucket="1_2"} 173
telemt_desync_frames_bucket_total{bucket="3_10"} 135
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 13594
telemt_me_refill_failed_total 220
telemt_me_writer_restored_same_endpoint_total 13199
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 387
telemt_user_connections_total{user="hello"} 115677
telemt_user_connections_current{user="hello"} 249
telemt_user_octets_from_client{user="hello"} 1794917687 (1.67 GB)
telemt_user_octets_to_client{user="hello"} 52209677946 (48.62 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 53169.9 (14h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 401382
telemt_connections_bad_total 47555
telemt_handshake_timeouts_total 3973
telemt_upstream_connect_attempt_total 10848
telemt_upstream_connect_success_total 10789
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 10848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5481
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 12019
telemt_me_reconnect_success_total 8140
telemt_me_reader_eof_total 8795
telemt_me_idle_close_by_peer_total 8795
telemt_me_route_drop_no_conn_total 269058
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 405786
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 568
telemt_desync_full_logged_total 230
telemt_desync_suppressed_total 338
telemt_desync_frames_bucket_total{bucket="1_2"} 153
telemt_desync_frames_bucket_total{bucket="3_10"} 211
telemt_desync_frames_bucket_total{bucket="gt_10"} 204
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 8384
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 8126
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 244
telemt_user_connections_total{user="hello"} 327679
telemt_user_connections_current{user="hello"} 758
telemt_user_octets_from_client{user="hello"} 4703080308 (4.38 GB)
telemt_user_octets_to_client{user="hello"} 181802378424 (169.32 GB)
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 936.9 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 957
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 222
telemt_upstream_connect_success_total 204
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 222
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 35
telemt_me_reconnect_success_total 17
telemt_me_reader_eof_total 9
telemt_me_idle_close_by_peer_total 9
telemt_me_route_drop_no_conn_total 172
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 767
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 22
telemt_me_writer_restored_same_endpoint_total 15
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 873
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 15152397 (14.45 MB)
telemt_user_octets_to_client{user="hello"} 3753381862 (3.50 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 8
```