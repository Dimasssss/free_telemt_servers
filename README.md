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

# Server Metrics 2026-03-16 17:21:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 13406.3 (3h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139212
telemt_connections_bad_total 619
telemt_handshake_timeouts_total 3837
telemt_upstream_connect_attempt_total 2873
telemt_upstream_connect_success_total 2862
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2873
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1499
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3318
telemt_me_reconnect_success_total 2147
telemt_me_reader_eof_total 2226
telemt_me_idle_close_by_peer_total 2225
telemt_me_route_drop_no_conn_total 42047
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 130166
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 688
telemt_desync_full_logged_total 158
telemt_desync_suppressed_total 530
telemt_desync_frames_bucket_total{bucket="1_2"} 251
telemt_desync_frames_bucket_total{bucket="3_10"} 249
telemt_desync_frames_bucket_total{bucket="gt_10"} 188
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2197
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2145
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 130089
telemt_user_connections_current{user="hello"} 627
telemt_user_octets_from_client{user="hello"} 2400711472 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 75587339160 (70.40 GB)
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 8184.4 (2h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58582
telemt_connections_bad_total 493
telemt_handshake_timeouts_total 2900
telemt_upstream_connect_attempt_total 1738
telemt_upstream_connect_success_total 1726
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1738
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 952
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 4768
telemt_me_reconnect_success_total 1262
telemt_me_reader_eof_total 1385
telemt_me_idle_close_by_peer_total 1385
telemt_me_route_drop_no_conn_total 35318
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53135
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 104
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 78
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1395
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 1257
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 343
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 53088
telemt_user_connections_current{user="hello"} 380
telemt_user_octets_from_client{user="hello"} 672207148 (641.07 MB)
telemt_user_octets_to_client{user="hello"} 16080189972 (14.98 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 13519.1 (3h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54623
telemt_connections_bad_total 76
telemt_handshake_timeouts_total 837
telemt_upstream_connect_attempt_total 3878
telemt_upstream_connect_success_total 3834
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 3878
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1720
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_reconnect_attempts_total 39903
telemt_me_reconnect_success_total 2140
telemt_me_reader_eof_total 2429
telemt_me_idle_close_by_peer_total 2429
telemt_me_route_drop_no_conn_total 19221
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49972
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 145
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 63
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2435
telemt_me_refill_failed_total 1179
telemt_me_writer_restored_same_endpoint_total 2096
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 295
telemt_user_connections_total{user="hello"} 50913
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 646674950 (616.72 MB)
telemt_user_octets_to_client{user="hello"} 14260351890 (13.28 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 13655.3 (3h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108040
telemt_connections_bad_total 205
telemt_handshake_timeouts_total 1718
telemt_upstream_connect_attempt_total 3003
telemt_upstream_connect_success_total 2978
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 3003
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1525
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_reconnect_attempts_total 8545
telemt_me_reconnect_success_total 2190
telemt_me_reader_eof_total 2423
telemt_me_idle_close_by_peer_total 2422
telemt_me_route_drop_no_conn_total 40356
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 102297
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 577
telemt_desync_full_logged_total 156
telemt_desync_suppressed_total 421
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 252
telemt_desync_frames_bucket_total{bucket="gt_10"} 233
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2417
telemt_me_refill_failed_total 197
telemt_me_writer_restored_same_endpoint_total 2186
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 102272
telemt_user_connections_current{user="hello"} 424
telemt_user_octets_from_client{user="hello"} 1398955944 (1.30 GB)
telemt_user_octets_to_client{user="hello"} 26563508748 (24.74 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 11115.7 (3h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63020
telemt_connections_bad_total 19862
telemt_handshake_timeouts_total 541
telemt_upstream_connect_attempt_total 2821
telemt_upstream_connect_success_total 2783
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 2821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1595
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_reconnect_attempts_total 3825
telemt_me_reconnect_success_total 2171
telemt_me_reader_eof_total 2278
telemt_me_idle_close_by_peer_total 2278
telemt_me_route_drop_no_conn_total 48510
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59336
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2259
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 2171
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 40389
telemt_user_connections_current{user="hello"} 219
telemt_user_octets_from_client{user="hello"} 1987373164 (1.85 GB)
telemt_user_octets_to_client{user="hello"} 29853759708 (27.80 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 13224.0 (3h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155762
telemt_connections_bad_total 1985
telemt_handshake_timeouts_total 3330
telemt_upstream_connect_attempt_total 2827
telemt_upstream_connect_success_total 2827
telemt_upstream_connect_attempts_per_request{bucket="1"} 2827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1453
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 7139
telemt_me_reconnect_success_total 2114
telemt_me_reader_eof_total 2307
telemt_me_idle_close_by_peer_total 2306
telemt_me_route_drop_no_conn_total 70284
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 144041
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 49
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2288
telemt_me_refill_failed_total 156
telemt_me_writer_restored_same_endpoint_total 2108
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 174
telemt_user_connections_total{user="hello"} 143758
telemt_user_connections_current{user="hello"} 719
telemt_user_octets_from_client{user="hello"} 2973183868 (2.77 GB)
telemt_user_octets_to_client{user="hello"} 53668799156 (49.98 GB)
telemt_user_unique_ips_current{user="hello"} 258
telemt_user_unique_ips_recent_window{user="hello"} 81
```