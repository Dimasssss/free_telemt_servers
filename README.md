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

# Server Metrics 2026-03-19 02:08:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 15589.6 (4h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 186725
telemt_connections_bad_total 22813
telemt_connections_current 649
telemt_connections_me_current 649
telemt_handshake_timeouts_total 8358
telemt_upstream_connect_attempt_total 3146
telemt_upstream_connect_success_total 3093
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 3146
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1469
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1621
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2299
telemt_me_reconnect_success_total 2290
telemt_me_reader_eof_total 2394
telemt_me_idle_close_by_peer_total 2394
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 52264
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 147250
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 980
telemt_desync_full_logged_total 256
telemt_desync_suppressed_total 724
telemt_desync_frames_bucket_total{bucket="1_2"} 368
telemt_desync_frames_bucket_total{bucket="3_10"} 415
telemt_desync_frames_bucket_total{bucket="gt_10"} 197
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2299
telemt_me_writer_restored_same_endpoint_total 2276
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 144478
telemt_user_connections_current{user="hello"} 649
telemt_user_octets_from_client{user="hello"} 1573590588 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 47181664448 (43.94 GB)
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 15593.3 (4h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 342757
telemt_connections_bad_total 22621
telemt_connections_current 1600
telemt_connections_me_current 1600
telemt_handshake_timeouts_total 6591
telemt_upstream_connect_attempt_total 3049
telemt_upstream_connect_success_total 2994
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 3049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1407
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1580
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_reconnect_attempts_total 2192
telemt_me_reconnect_success_total 2182
telemt_me_reader_eof_total 2297
telemt_me_idle_close_by_peer_total 2297
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 106081
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 293599
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1082
telemt_desync_full_logged_total 363
telemt_desync_suppressed_total 719
telemt_desync_frames_bucket_total{bucket="1_2"} 243
telemt_desync_frames_bucket_total{bucket="3_10"} 413
telemt_desync_frames_bucket_total{bucket="gt_10"} 426
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2220
telemt_me_writer_restored_same_endpoint_total 2167
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 293643
telemt_user_connections_current{user="hello"} 1600
telemt_user_octets_from_client{user="hello"} 11592265840 (10.80 GB)
telemt_user_octets_to_client{user="hello"} 113115124440 (105.35 GB)
telemt_user_unique_ips_current{user="hello"} 629
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 15590.4 (4h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 278208
telemt_connections_bad_total 52920
telemt_connections_current 1171
telemt_connections_me_current 1171
telemt_handshake_timeouts_total 6477
telemt_upstream_connect_attempt_total 3030
telemt_upstream_connect_success_total 3030
telemt_upstream_connect_attempts_per_request{bucket="1"} 3030
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1497
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 2226
telemt_me_reconnect_success_total 2218
telemt_me_reader_eof_total 2343
telemt_me_idle_close_by_peer_total 2343
telemt_me_route_drop_no_conn_total 84559
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 210902
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1023
telemt_desync_full_logged_total 367
telemt_desync_suppressed_total 656
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 414
telemt_desync_frames_bucket_total{bucket="gt_10"} 433
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2251
telemt_me_writer_restored_same_endpoint_total 2202
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 210890
telemt_user_connections_current{user="hello"} 1171
telemt_user_octets_from_client{user="hello"} 2567940872 (2.39 GB)
telemt_user_octets_to_client{user="hello"} 123464318272 (114.99 GB)
telemt_user_unique_ips_current{user="hello"} 502
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 15643.8 (4h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 318614
telemt_connections_bad_total 31206
telemt_connections_current 995
telemt_connections_me_current 995
telemt_handshake_timeouts_total 5177
telemt_upstream_connect_attempt_total 2895
telemt_upstream_connect_success_total 2895
telemt_upstream_connect_attempts_per_request{bucket="1"} 2895
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1486
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1401
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 2094
telemt_me_reconnect_success_total 2085
telemt_me_reader_eof_total 2194
telemt_me_idle_close_by_peer_total 2194
telemt_me_route_drop_no_conn_total 97369
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 211918
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 572
telemt_desync_full_logged_total 211
telemt_desync_suppressed_total 361
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 230
telemt_desync_frames_bucket_total{bucket="gt_10"} 231
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2111
telemt_me_writer_restored_same_endpoint_total 2061
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 211831
telemt_user_connections_current{user="hello"} 995
telemt_user_octets_from_client{user="hello"} 1949090148 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 71991708328 (67.05 GB)
telemt_user_unique_ips_current{user="hello"} 406
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 15587.2 (4h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 300459
telemt_connections_bad_total 17575
telemt_connections_current 1253
telemt_connections_me_current 1253
telemt_handshake_timeouts_total 9848
telemt_upstream_connect_attempt_total 2980
telemt_upstream_connect_success_total 2964
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 2980
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1427
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1526
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 2164
telemt_me_reconnect_success_total 2151
telemt_me_reader_eof_total 2266
telemt_me_idle_close_by_peer_total 2266
telemt_me_route_drop_no_conn_total 92198
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 231250
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 942
telemt_desync_full_logged_total 353
telemt_desync_suppressed_total 589
telemt_desync_frames_bucket_total{bucket="1_2"} 252
telemt_desync_frames_bucket_total{bucket="3_10"} 341
telemt_desync_frames_bucket_total{bucket="gt_10"} 349
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2163
telemt_me_writer_restored_same_endpoint_total 2127
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 231174
telemt_user_connections_current{user="hello"} 1253
telemt_user_octets_from_client{user="hello"} 6823651348 (6.36 GB)
telemt_user_octets_to_client{user="hello"} 126922176232 (118.21 GB)
telemt_user_unique_ips_current{user="hello"} 548
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 15598.6 (4h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74755
telemt_connections_bad_total 9280
telemt_connections_current 321
telemt_connections_me_current 321
telemt_handshake_timeouts_total 317
telemt_upstream_connect_attempt_total 4513
telemt_upstream_connect_success_total 4374
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 4513
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2303
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_reconnect_attempts_total 5402
telemt_me_reconnect_success_total 3569
telemt_me_reader_eof_total 3721
telemt_me_idle_close_by_peer_total 3721
telemt_me_route_drop_no_conn_total 29708
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62978
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 27
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 3619
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 3539
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 62977
telemt_user_connections_current{user="hello"} 321
telemt_user_octets_from_client{user="hello"} 1335588768 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 44713667340 (41.64 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 15589.5 (4h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211731
telemt_connections_bad_total 23133
telemt_connections_current 1116
telemt_connections_me_current 1116
telemt_handshake_timeouts_total 10063
telemt_upstream_connect_attempt_total 3378
telemt_upstream_connect_success_total 3378
telemt_upstream_connect_attempts_per_request{bucket="1"} 3378
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1789
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1587
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 2577
telemt_me_reconnect_success_total 2568
telemt_me_reader_eof_total 2701
telemt_me_idle_close_by_peer_total 2701
telemt_me_route_drop_no_conn_total 62577
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 173428
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1050
telemt_desync_full_logged_total 411
telemt_desync_suppressed_total 639
telemt_desync_frames_bucket_total{bucket="1_2"} 193
telemt_desync_frames_bucket_total{bucket="3_10"} 425
telemt_desync_frames_bucket_total{bucket="gt_10"} 432
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2598
telemt_me_writer_restored_same_endpoint_total 2553
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 173452
telemt_user_connections_current{user="hello"} 1116
telemt_user_octets_from_client{user="hello"} 1784931228 (1.66 GB)
telemt_user_octets_to_client{user="hello"} 88366687324 (82.30 GB)
telemt_user_unique_ips_current{user="hello"} 451
telemt_user_unique_ips_recent_window{user="hello"} 101
```