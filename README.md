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

# Server Metrics 2026-03-19 02:03:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 15283.0 (4h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 180383
telemt_connections_bad_total 21690
telemt_connections_current 673
telemt_connections_me_current 673
telemt_handshake_timeouts_total 6920
telemt_upstream_connect_attempt_total 3043
telemt_upstream_connect_success_total 2994
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 3043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1416
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1575
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2243
telemt_me_reconnect_success_total 2234
telemt_me_reader_eof_total 2329
telemt_me_idle_close_by_peer_total 2329
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 51318
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 144038
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 941
telemt_desync_full_logged_total 246
telemt_desync_suppressed_total 695
telemt_desync_frames_bucket_total{bucket="1_2"} 347
telemt_desync_frames_bucket_total{bucket="3_10"} 402
telemt_desync_frames_bucket_total{bucket="gt_10"} 192
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2241
telemt_me_writer_restored_same_endpoint_total 2220
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 141268
telemt_user_connections_current{user="hello"} 673
telemt_user_octets_from_client{user="hello"} 1556750196 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 46080199048 (42.92 GB)
telemt_user_unique_ips_current{user="hello"} 274
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 15286.8 (4h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 336380
telemt_connections_bad_total 22334
telemt_connections_current 1578
telemt_connections_me_current 1578
telemt_handshake_timeouts_total 6290
telemt_upstream_connect_attempt_total 2950
telemt_upstream_connect_success_total 2895
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 2950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1531
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_reconnect_attempts_total 2136
telemt_me_reconnect_success_total 2127
telemt_me_reader_eof_total 2238
telemt_me_idle_close_by_peer_total 2238
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 104412
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 288225
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1053
telemt_desync_full_logged_total 354
telemt_desync_suppressed_total 699
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 400
telemt_desync_frames_bucket_total{bucket="gt_10"} 417
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2165
telemt_me_writer_restored_same_endpoint_total 2113
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 288269
telemt_user_connections_current{user="hello"} 1578
telemt_user_octets_from_client{user="hello"} 11551040756 (10.76 GB)
telemt_user_octets_to_client{user="hello"} 110382085668 (102.80 GB)
telemt_user_unique_ips_current{user="hello"} 635
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 15283.8 (4h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 272247
telemt_connections_bad_total 51380
telemt_connections_current 1137
telemt_connections_me_current 1137
telemt_handshake_timeouts_total 6450
telemt_upstream_connect_attempt_total 2925
telemt_upstream_connect_success_total 2925
telemt_upstream_connect_attempts_per_request{bucket="1"} 2925
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1474
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1447
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2165
telemt_me_reconnect_success_total 2158
telemt_me_reader_eof_total 2274
telemt_me_idle_close_by_peer_total 2274
telemt_me_route_drop_no_conn_total 83052
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 206627
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1000
telemt_desync_full_logged_total 362
telemt_desync_suppressed_total 638
telemt_desync_frames_bucket_total{bucket="1_2"} 174
telemt_desync_frames_bucket_total{bucket="3_10"} 402
telemt_desync_frames_bucket_total{bucket="gt_10"} 424
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2189
telemt_me_writer_restored_same_endpoint_total 2142
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 206615
telemt_user_connections_current{user="hello"} 1137
telemt_user_octets_from_client{user="hello"} 2521706780 (2.35 GB)
telemt_user_octets_to_client{user="hello"} 121761123596 (113.40 GB)
telemt_user_unique_ips_current{user="hello"} 504
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 15337.3 (4h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 310159
telemt_connections_bad_total 29566
telemt_connections_current 1070
telemt_connections_me_current 1070
telemt_handshake_timeouts_total 5125
telemt_upstream_connect_attempt_total 2795
telemt_upstream_connect_success_total 2795
telemt_upstream_connect_attempts_per_request{bucket="1"} 2795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1355
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 2028
telemt_me_reconnect_success_total 2020
telemt_me_reader_eof_total 2121
telemt_me_idle_close_by_peer_total 2121
telemt_me_route_drop_no_conn_total 96334
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 208379
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 571
telemt_desync_full_logged_total 211
telemt_desync_suppressed_total 360
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 230
telemt_desync_frames_bucket_total{bucket="gt_10"} 230
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2045
telemt_me_writer_restored_same_endpoint_total 1996
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 208294
telemt_user_connections_current{user="hello"} 1070
telemt_user_octets_from_client{user="hello"} 1916540156 (1.78 GB)
telemt_user_octets_to_client{user="hello"} 69964657588 (65.16 GB)
telemt_user_unique_ips_current{user="hello"} 430
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 15280.5 (4h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 294873
telemt_connections_bad_total 17362
telemt_connections_current 1265
telemt_connections_me_current 1265
telemt_handshake_timeouts_total 9676
telemt_upstream_connect_attempt_total 2873
telemt_upstream_connect_success_total 2857
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 2873
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1474
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 2100
telemt_me_reconnect_success_total 2088
telemt_me_reader_eof_total 2192
telemt_me_idle_close_by_peer_total 2192
telemt_me_route_drop_no_conn_total 90733
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 226494
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 907
telemt_desync_full_logged_total 341
telemt_desync_suppressed_total 566
telemt_desync_frames_bucket_total{bucket="1_2"} 241
telemt_desync_frames_bucket_total{bucket="3_10"} 325
telemt_desync_frames_bucket_total{bucket="gt_10"} 341
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2099
telemt_me_writer_restored_same_endpoint_total 2064
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 226418
telemt_user_connections_current{user="hello"} 1265
telemt_user_octets_from_client{user="hello"} 6777947664 (6.31 GB)
telemt_user_octets_to_client{user="hello"} 124925442652 (116.35 GB)
telemt_user_unique_ips_current{user="hello"} 554
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 15291.9 (4h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73454
telemt_connections_bad_total 9278
telemt_connections_current 407
telemt_connections_me_current 407
telemt_handshake_timeouts_total 258
telemt_upstream_connect_attempt_total 4338
telemt_upstream_connect_success_total 4209
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 4338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1981
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_reconnect_attempts_total 5280
telemt_me_reconnect_success_total 3449
telemt_me_reader_eof_total 3601
telemt_me_idle_close_by_peer_total 3601
telemt_me_route_drop_no_conn_total 29076
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61797
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
telemt_me_writer_removed_unexpected_total 3499
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 3419
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 61797
telemt_user_connections_current{user="hello"} 407
telemt_user_octets_from_client{user="hello"} 919065392 (876.49 MB)
telemt_user_octets_to_client{user="hello"} 43524668964 (40.54 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 15283.0 (4h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 208026
telemt_connections_bad_total 22920
telemt_connections_current 1053
telemt_connections_me_current 1053
telemt_handshake_timeouts_total 9806
telemt_upstream_connect_attempt_total 3262
telemt_upstream_connect_success_total 3262
telemt_upstream_connect_attempts_per_request{bucket="1"} 3262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1721
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1539
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 2504
telemt_me_reconnect_success_total 2496
telemt_me_reader_eof_total 2623
telemt_me_idle_close_by_peer_total 2623
telemt_me_route_drop_no_conn_total 61656
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 170283
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1032
telemt_desync_full_logged_total 406
telemt_desync_suppressed_total 626
telemt_desync_frames_bucket_total{bucket="1_2"} 187
telemt_desync_frames_bucket_total{bucket="3_10"} 419
telemt_desync_frames_bucket_total{bucket="gt_10"} 426
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2526
telemt_me_writer_restored_same_endpoint_total 2481
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 170307
telemt_user_connections_current{user="hello"} 1053
telemt_user_octets_from_client{user="hello"} 1724811776 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 87125269828 (81.14 GB)
telemt_user_unique_ips_current{user="hello"} 437
telemt_user_unique_ips_recent_window{user="hello"} 101
```