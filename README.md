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

# Server Metrics 2026-03-19 01:37:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 13749.2 (3h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157878
telemt_connections_bad_total 19487
telemt_connections_current 689
telemt_connections_me_current 689
telemt_handshake_timeouts_total 3558
telemt_upstream_connect_attempt_total 2792
telemt_upstream_connect_success_total 2745
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 2792
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1431
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2037
telemt_me_reconnect_success_total 2031
telemt_me_reader_eof_total 2116
telemt_me_idle_close_by_peer_total 2116
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 46913
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128092
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 820
telemt_desync_full_logged_total 214
telemt_desync_suppressed_total 606
telemt_desync_frames_bucket_total{bucket="1_2"} 303
telemt_desync_frames_bucket_total{bucket="3_10"} 341
telemt_desync_frames_bucket_total{bucket="gt_10"} 176
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2036
telemt_me_writer_restored_same_endpoint_total 2017
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 125322
telemt_user_connections_current{user="hello"} 689
telemt_user_octets_from_client{user="hello"} 1276196872 (1.19 GB)
telemt_user_octets_to_client{user="hello"} 41301276504 (38.46 GB)
telemt_user_unique_ips_current{user="hello"} 262
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 13753.0 (3h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 308269
telemt_connections_bad_total 21175
telemt_connections_current 1435
telemt_connections_me_current 1435
telemt_handshake_timeouts_total 5296
telemt_upstream_connect_attempt_total 2663
telemt_upstream_connect_success_total 2611
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 2663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1367
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_reconnect_attempts_total 1895
telemt_me_reconnect_success_total 1888
telemt_me_reader_eof_total 1985
telemt_me_idle_close_by_peer_total 1985
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 95949
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 263940
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 944
telemt_desync_full_logged_total 323
telemt_desync_suppressed_total 621
telemt_desync_frames_bucket_total{bucket="1_2"} 222
telemt_desync_frames_bucket_total{bucket="3_10"} 344
telemt_desync_frames_bucket_total{bucket="gt_10"} 378
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1921
telemt_me_writer_restored_same_endpoint_total 1875
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 263981
telemt_user_connections_current{user="hello"} 1435
telemt_user_octets_from_client{user="hello"} 11200789776 (10.43 GB)
telemt_user_octets_to_client{user="hello"} 101080275596 (94.14 GB)
telemt_user_unique_ips_current{user="hello"} 577
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 13750.4 (3h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 246890
telemt_connections_bad_total 44926
telemt_connections_current 1041
telemt_connections_me_current 1041
telemt_handshake_timeouts_total 6305
telemt_upstream_connect_attempt_total 2697
telemt_upstream_connect_success_total 2697
telemt_upstream_connect_attempts_per_request{bucket="1"} 2697
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1339
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1982
telemt_me_reconnect_success_total 1976
telemt_me_reader_eof_total 2083
telemt_me_idle_close_by_peer_total 2083
telemt_me_route_drop_no_conn_total 77632
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 188433
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 904
telemt_desync_full_logged_total 332
telemt_desync_suppressed_total 572
telemt_desync_frames_bucket_total{bucket="1_2"} 166
telemt_desync_frames_bucket_total{bucket="3_10"} 364
telemt_desync_frames_bucket_total{bucket="gt_10"} 374
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2006
telemt_me_writer_restored_same_endpoint_total 1960
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 188424
telemt_user_connections_current{user="hello"} 1041
telemt_user_octets_from_client{user="hello"} 2311054728 (2.15 GB)
telemt_user_octets_to_client{user="hello"} 112153414664 (104.45 GB)
telemt_user_unique_ips_current{user="hello"} 460
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 13803.5 (3h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 274092
telemt_connections_bad_total 27880
telemt_connections_current 945
telemt_connections_me_current 945
telemt_handshake_timeouts_total 4725
telemt_upstream_connect_attempt_total 2558
telemt_upstream_connect_success_total 2558
telemt_upstream_connect_attempts_per_request{bucket="1"} 2558
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1233
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 1844
telemt_me_reconnect_success_total 1838
telemt_me_reader_eof_total 1926
telemt_me_idle_close_by_peer_total 1926
telemt_me_route_drop_no_conn_total 82828
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 190181
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 539
telemt_desync_full_logged_total 196
telemt_desync_suppressed_total 343
telemt_desync_frames_bucket_total{bucket="1_2"} 108
telemt_desync_frames_bucket_total{bucket="3_10"} 216
telemt_desync_frames_bucket_total{bucket="gt_10"} 215
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 1858
telemt_me_writer_restored_same_endpoint_total 1814
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 190099
telemt_user_connections_current{user="hello"} 945
telemt_user_octets_from_client{user="hello"} 1803955884 (1.68 GB)
telemt_user_octets_to_client{user="hello"} 64184853284 (59.78 GB)
telemt_user_unique_ips_current{user="hello"} 408
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 13747.0 (3h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 269700
telemt_connections_bad_total 16269
telemt_connections_current 1179
telemt_connections_me_current 1179
telemt_handshake_timeouts_total 9008
telemt_upstream_connect_attempt_total 2601
telemt_upstream_connect_success_total 2587
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2601
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1254
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1325
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 1873
telemt_me_reconnect_success_total 1862
telemt_me_reader_eof_total 1955
telemt_me_idle_close_by_peer_total 1955
telemt_me_route_drop_no_conn_total 83699
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 205961
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 825
telemt_desync_full_logged_total 314
telemt_desync_suppressed_total 511
telemt_desync_frames_bucket_total{bucket="1_2"} 217
telemt_desync_frames_bucket_total{bucket="3_10"} 291
telemt_desync_frames_bucket_total{bucket="gt_10"} 317
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 1872
telemt_me_writer_restored_same_endpoint_total 1838
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 205884
telemt_user_connections_current{user="hello"} 1179
telemt_user_octets_from_client{user="hello"} 5413692764 (5.04 GB)
telemt_user_octets_to_client{user="hello"} 115703512316 (107.76 GB)
telemt_user_unique_ips_current{user="hello"} 525
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 13758.5 (3h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67711
telemt_connections_bad_total 9233
telemt_connections_current 325
telemt_connections_me_current 325
telemt_handshake_timeouts_total 246
telemt_upstream_connect_attempt_total 3949
telemt_upstream_connect_success_total 3830
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 3949
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2017
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_reconnect_attempts_total 4944
telemt_me_reconnect_success_total 3114
telemt_me_reader_eof_total 3264
telemt_me_idle_close_by_peer_total 3264
telemt_me_route_drop_no_conn_total 26150
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56444
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
telemt_me_writer_removed_unexpected_total 3162
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 3084
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 56444
telemt_user_connections_current{user="hello"} 325
telemt_user_octets_from_client{user="hello"} 804130968 (766.88 MB)
telemt_user_octets_to_client{user="hello"} 37251478548 (34.69 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 13749.3 (3h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190836
telemt_connections_bad_total 21753
telemt_connections_current 1080
telemt_connections_me_current 1080
telemt_handshake_timeouts_total 8815
telemt_upstream_connect_attempt_total 2964
telemt_upstream_connect_success_total 2964
telemt_upstream_connect_attempts_per_request{bucket="1"} 2964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1407
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 2249
telemt_me_reconnect_success_total 2242
telemt_me_reader_eof_total 2355
telemt_me_idle_close_by_peer_total 2355
telemt_me_route_drop_no_conn_total 56640
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 155782
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 974
telemt_desync_full_logged_total 387
telemt_desync_suppressed_total 587
telemt_desync_frames_bucket_total{bucket="1_2"} 173
telemt_desync_frames_bucket_total{bucket="3_10"} 391
telemt_desync_frames_bucket_total{bucket="gt_10"} 410
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2267
telemt_me_writer_restored_same_endpoint_total 2227
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 155805
telemt_user_connections_current{user="hello"} 1080
telemt_user_octets_from_client{user="hello"} 1608259836 (1.50 GB)
telemt_user_octets_to_client{user="hello"} 81561696388 (75.96 GB)
telemt_user_unique_ips_current{user="hello"} 431
telemt_user_unique_ips_recent_window{user="hello"} 83
```