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

# Server Metrics 2026-03-19 02:33:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 17123.5 (4h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 209005
telemt_connections_bad_total 25138
telemt_connections_current 719
telemt_connections_me_current 719
telemt_handshake_timeouts_total 12750
telemt_upstream_connect_attempt_total 3376
telemt_upstream_connect_success_total 3322
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 3376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1731
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2484
telemt_me_reconnect_success_total 2473
telemt_me_reader_eof_total 2585
telemt_me_idle_close_by_peer_total 2585
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 57389
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161928
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1120
telemt_desync_full_logged_total 297
telemt_desync_suppressed_total 823
telemt_desync_frames_bucket_total{bucket="1_2"} 416
telemt_desync_frames_bucket_total{bucket="3_10"} 478
telemt_desync_frames_bucket_total{bucket="gt_10"} 226
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2484
telemt_me_writer_restored_same_endpoint_total 2458
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 159155
telemt_user_connections_current{user="hello"} 719
telemt_user_octets_from_client{user="hello"} 1715744980 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 51120121000 (47.61 GB)
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 17127.5 (4h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 373554
telemt_connections_bad_total 23273
telemt_connections_current 1680
telemt_connections_me_current 1680
telemt_handshake_timeouts_total 8895
telemt_upstream_connect_attempt_total 3284
telemt_upstream_connect_success_total 3227
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 3284
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1512
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1707
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 2378
telemt_me_reconnect_success_total 2368
telemt_me_reader_eof_total 2492
telemt_me_idle_close_by_peer_total 2492
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 114492
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 319228
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1169
telemt_desync_full_logged_total 387
telemt_desync_suppressed_total 782
telemt_desync_frames_bucket_total{bucket="1_2"} 266
telemt_desync_frames_bucket_total{bucket="3_10"} 448
telemt_desync_frames_bucket_total{bucket="gt_10"} 455
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2406
telemt_me_writer_restored_same_endpoint_total 2353
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 319267
telemt_user_connections_current{user="hello"} 1680
telemt_user_octets_from_client{user="hello"} 11814328072 (11.00 GB)
telemt_user_octets_to_client{user="hello"} 123699330024 (115.20 GB)
telemt_user_unique_ips_current{user="hello"} 664
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 17124.7 (4h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 303843
telemt_connections_bad_total 57727
telemt_connections_current 1220
telemt_connections_me_current 1220
telemt_handshake_timeouts_total 7171
telemt_upstream_connect_attempt_total 3272
telemt_upstream_connect_success_total 3272
telemt_upstream_connect_attempts_per_request{bucket="1"} 3272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1649
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1618
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 2419
telemt_me_reconnect_success_total 2411
telemt_me_reader_eof_total 2546
telemt_me_idle_close_by_peer_total 2546
telemt_me_route_drop_no_conn_total 91580
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 230366
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1185
telemt_desync_full_logged_total 435
telemt_desync_suppressed_total 750
telemt_desync_frames_bucket_total{bucket="1_2"} 208
telemt_desync_frames_bucket_total{bucket="3_10"} 485
telemt_desync_frames_bucket_total{bucket="gt_10"} 492
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2448
telemt_me_writer_restored_same_endpoint_total 2395
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 230355
telemt_user_connections_current{user="hello"} 1220
telemt_user_octets_from_client{user="hello"} 3834339716 (3.57 GB)
telemt_user_octets_to_client{user="hello"} 134841157648 (125.58 GB)
telemt_user_unique_ips_current{user="hello"} 513
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 17177.9 (4h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 359331
telemt_connections_bad_total 34594
telemt_connections_current 988
telemt_connections_me_current 988
telemt_handshake_timeouts_total 5449
telemt_upstream_connect_attempt_total 3147
telemt_upstream_connect_success_total 3147
telemt_upstream_connect_attempts_per_request{bucket="1"} 3147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1613
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1526
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 2270
telemt_me_reconnect_success_total 2259
telemt_me_reader_eof_total 2375
telemt_me_idle_close_by_peer_total 2375
telemt_me_route_drop_no_conn_total 103263
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 231253
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 594
telemt_desync_full_logged_total 218
telemt_desync_suppressed_total 376
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 235
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2288
telemt_me_writer_restored_same_endpoint_total 2235
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 231162
telemt_user_connections_current{user="hello"} 988
telemt_user_octets_from_client{user="hello"} 2089547244 (1.95 GB)
telemt_user_octets_to_client{user="hello"} 78983813152 (73.56 GB)
telemt_user_unique_ips_current{user="hello"} 425
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 17121.5 (4h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 326970
telemt_connections_bad_total 18625
telemt_connections_current 1176
telemt_connections_me_current 1176
telemt_handshake_timeouts_total 11227
telemt_upstream_connect_attempt_total 3229
telemt_upstream_connect_success_total 3211
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 3229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1544
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1656
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 2367
telemt_me_reconnect_success_total 2353
telemt_me_reader_eof_total 2478
telemt_me_idle_close_by_peer_total 2478
telemt_me_route_drop_no_conn_total 99786
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 251790
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1067
telemt_desync_full_logged_total 401
telemt_desync_suppressed_total 666
telemt_desync_frames_bucket_total{bucket="1_2"} 290
telemt_desync_frames_bucket_total{bucket="3_10"} 393
telemt_desync_frames_bucket_total{bucket="gt_10"} 384
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2366
telemt_me_writer_restored_same_endpoint_total 2329
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 251714
telemt_user_connections_current{user="hello"} 1176
telemt_user_octets_from_client{user="hello"} 8321019392 (7.75 GB)
telemt_user_octets_to_client{user="hello"} 139541493844 (129.96 GB)
telemt_user_unique_ips_current{user="hello"} 547
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 17132.8 (4h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81401
telemt_connections_bad_total 9337
telemt_connections_current 391
telemt_connections_me_current 391
telemt_handshake_timeouts_total 345
telemt_upstream_connect_attempt_total 4936
telemt_upstream_connect_success_total 4794
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 4936
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2513
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_reconnect_attempts_total 5774
telemt_me_reconnect_success_total 3940
telemt_me_reader_eof_total 4123
telemt_me_idle_close_by_peer_total 4123
telemt_me_route_drop_no_conn_total 32538
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 69118
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 34
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 3994
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 3910
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 69117
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 1534006240 (1.43 GB)
telemt_user_octets_to_client{user="hello"} 51267282048 (47.75 GB)
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 17123.8 (4h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 231719
telemt_connections_bad_total 24146
telemt_connections_current 1094
telemt_connections_me_current 1094
telemt_handshake_timeouts_total 11398
telemt_upstream_connect_attempt_total 3635
telemt_upstream_connect_success_total 3635
telemt_upstream_connect_attempts_per_request{bucket="1"} 3635
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1726
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 2790
telemt_me_reconnect_success_total 2781
telemt_me_reader_eof_total 2924
telemt_me_idle_close_by_peer_total 2924
telemt_me_route_drop_no_conn_total 67742
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 189986
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1073
telemt_desync_full_logged_total 417
telemt_desync_suppressed_total 656
telemt_desync_frames_bucket_total{bucket="1_2"} 199
telemt_desync_frames_bucket_total{bucket="3_10"} 434
telemt_desync_frames_bucket_total{bucket="gt_10"} 440
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2813
telemt_me_writer_restored_same_endpoint_total 2766
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 190010
telemt_user_connections_current{user="hello"} 1094
telemt_user_octets_from_client{user="hello"} 1974857124 (1.84 GB)
telemt_user_octets_to_client{user="hello"} 96830041152 (90.18 GB)
telemt_user_unique_ips_current{user="hello"} 443
telemt_user_unique_ips_recent_window{user="hello"} 101
```