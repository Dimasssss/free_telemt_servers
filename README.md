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

# Server Metrics 2026-03-16 17:06:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 12489.7 (3h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130640
telemt_connections_bad_total 618
telemt_handshake_timeouts_total 3758
telemt_upstream_connect_attempt_total 2704
telemt_upstream_connect_success_total 2694
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 2704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1293
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1398
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3193
telemt_me_reconnect_success_total 2023
telemt_me_reader_eof_total 2091
telemt_me_idle_close_by_peer_total 2091
telemt_me_route_drop_no_conn_total 39533
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 121940
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 643
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 498
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 229
telemt_desync_frames_bucket_total{bucket="gt_10"} 167
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2072
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2021
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 121866
telemt_user_connections_current{user="hello"} 660
telemt_user_octets_from_client{user="hello"} 2224440516 (2.07 GB)
telemt_user_octets_to_client{user="hello"} 70158051448 (65.34 GB)
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 7268.4 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51516
telemt_connections_bad_total 413
telemt_handshake_timeouts_total 2550
telemt_upstream_connect_attempt_total 1577
telemt_upstream_connect_success_total 1566
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1577
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 870
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 4662
telemt_me_reconnect_success_total 1157
telemt_me_reader_eof_total 1268
telemt_me_idle_close_by_peer_total 1268
telemt_me_route_drop_no_conn_total 32133
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46868
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 95
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 71
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1287
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 1152
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 343
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 46823
telemt_user_connections_current{user="hello"} 406
telemt_user_octets_from_client{user="hello"} 621091928 (592.32 MB)
telemt_user_octets_to_client{user="hello"} 14819998744 (13.80 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 12602.9 (3h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51330
telemt_connections_bad_total 60
telemt_handshake_timeouts_total 784
telemt_upstream_connect_attempt_total 3583
telemt_upstream_connect_success_total 3540
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 3583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1956
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1561
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_reconnect_attempts_total 39653
telemt_me_reconnect_success_total 1892
telemt_me_reader_eof_total 2181
telemt_me_idle_close_by_peer_total 2181
telemt_me_route_drop_no_conn_total 17937
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46819
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 135
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 84
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2184
telemt_me_refill_failed_total 1179
telemt_me_writer_restored_same_endpoint_total 1848
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 292
telemt_user_connections_total{user="hello"} 47761
telemt_user_connections_current{user="hello"} 259
telemt_user_octets_from_client{user="hello"} 598910374 (571.17 MB)
telemt_user_octets_to_client{user="hello"} 12562853874 (11.70 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 12739.0 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100755
telemt_connections_bad_total 189
telemt_handshake_timeouts_total 1709
telemt_upstream_connect_attempt_total 2731
telemt_upstream_connect_success_total 2707
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 2730
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1395
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_reconnect_attempts_total 8317
telemt_me_reconnect_success_total 1963
telemt_me_reader_eof_total 2185
telemt_me_idle_close_by_peer_total 2185
telemt_me_route_drop_no_conn_total 38332
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95307
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 551
telemt_desync_full_logged_total 148
telemt_desync_suppressed_total 403
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 221
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2186
telemt_me_refill_failed_total 197
telemt_me_writer_restored_same_endpoint_total 1959
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 223
telemt_user_connections_total{user="hello"} 95284
telemt_user_connections_current{user="hello"} 493
telemt_user_octets_from_client{user="hello"} 1325411916 (1.23 GB)
telemt_user_octets_to_client{user="hello"} 24692892620 (23.00 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 10199.3 (2h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59060
telemt_connections_bad_total 19330
telemt_handshake_timeouts_total 475
telemt_upstream_connect_attempt_total 2604
telemt_upstream_connect_success_total 2568
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 2604
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1033
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1475
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_reconnect_attempts_total 3653
telemt_me_reconnect_success_total 2001
telemt_me_reader_eof_total 2097
telemt_me_idle_close_by_peer_total 2097
telemt_me_route_drop_no_conn_total 47267
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56175
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_hardswap_pending_ttl_expired_total 1
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
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2086
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 2001
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 37228
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 1953722540 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 28089172300 (26.16 GB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 12307.0 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144468
telemt_connections_bad_total 1748
telemt_handshake_timeouts_total 3156
telemt_upstream_connect_attempt_total 2692
telemt_upstream_connect_success_total 2692
telemt_upstream_connect_attempts_per_request{bucket="1"} 2692
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 7047
telemt_me_reconnect_success_total 2024
telemt_me_reader_eof_total 2207
telemt_me_idle_close_by_peer_total 2207
telemt_me_route_drop_no_conn_total 66010
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 133822
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 48
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2193
telemt_me_refill_failed_total 156
telemt_me_writer_restored_same_endpoint_total 2019
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 133539
telemt_user_connections_current{user="hello"} 755
telemt_user_octets_from_client{user="hello"} 2864281164 (2.67 GB)
telemt_user_octets_to_client{user="hello"} 49958428524 (46.53 GB)
telemt_user_unique_ips_current{user="hello"} 254
telemt_user_unique_ips_recent_window{user="hello"} 102
```