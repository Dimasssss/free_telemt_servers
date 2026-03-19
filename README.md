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

# Server Metrics 2026-03-19 02:23:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 16509.8 (4h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 200051
telemt_connections_bad_total 24223
telemt_connections_current 652
telemt_connections_me_current 652
telemt_handshake_timeouts_total 10610
telemt_upstream_connect_attempt_total 3324
telemt_upstream_connect_success_total 3270
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 3324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1712
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2433
telemt_me_reconnect_success_total 2423
telemt_me_reader_eof_total 2533
telemt_me_idle_close_by_peer_total 2533
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 55209
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 156363
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1058
telemt_desync_full_logged_total 281
telemt_desync_suppressed_total 777
telemt_desync_frames_bucket_total{bucket="1_2"} 389
telemt_desync_frames_bucket_total{bucket="3_10"} 454
telemt_desync_frames_bucket_total{bucket="gt_10"} 215
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2432
telemt_me_writer_restored_same_endpoint_total 2408
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 153589
telemt_user_connections_current{user="hello"} 652
telemt_user_octets_from_client{user="hello"} 1663811800 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 49618894236 (46.21 GB)
telemt_user_unique_ips_current{user="hello"} 281
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 16513.6 (4h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 360893
telemt_connections_bad_total 23024
telemt_connections_current 1489
telemt_connections_me_current 1489
telemt_handshake_timeouts_total 8039
telemt_upstream_connect_attempt_total 3230
telemt_upstream_connect_success_total 3172
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 3229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1664
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 2327
telemt_me_reconnect_success_total 2316
telemt_me_reader_eof_total 2441
telemt_me_idle_close_by_peer_total 2441
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 111342
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 308800
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1132
telemt_desync_full_logged_total 377
telemt_desync_suppressed_total 755
telemt_desync_frames_bucket_total{bucket="1_2"} 253
telemt_desync_frames_bucket_total{bucket="3_10"} 434
telemt_desync_frames_bucket_total{bucket="gt_10"} 445
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2355
telemt_me_writer_restored_same_endpoint_total 2301
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 308839
telemt_user_connections_current{user="hello"} 1489
telemt_user_octets_from_client{user="hello"} 11727193040 (10.92 GB)
telemt_user_octets_to_client{user="hello"} 120169971908 (111.92 GB)
telemt_user_unique_ips_current{user="hello"} 618
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 16510.9 (4h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 293641
telemt_connections_bad_total 55844
telemt_connections_current 1169
telemt_connections_me_current 1169
telemt_handshake_timeouts_total 6832
telemt_upstream_connect_attempt_total 3210
telemt_upstream_connect_success_total 3210
telemt_upstream_connect_attempts_per_request{bucket="1"} 3210
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1622
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1583
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 2363
telemt_me_reconnect_success_total 2355
telemt_me_reader_eof_total 2488
telemt_me_idle_close_by_peer_total 2488
telemt_me_route_drop_no_conn_total 88950
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 222568
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1131
telemt_desync_full_logged_total 413
telemt_desync_suppressed_total 718
telemt_desync_frames_bucket_total{bucket="1_2"} 203
telemt_desync_frames_bucket_total{bucket="3_10"} 459
telemt_desync_frames_bucket_total{bucket="gt_10"} 469
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2390
telemt_me_writer_restored_same_endpoint_total 2339
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 222554
telemt_user_connections_current{user="hello"} 1169
telemt_user_octets_from_client{user="hello"} 3101906792 (2.89 GB)
telemt_user_octets_to_client{user="hello"} 129464872932 (120.57 GB)
telemt_user_unique_ips_current{user="hello"} 499
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 16564.2 (4h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 344660
telemt_connections_bad_total 34139
telemt_connections_current 986
telemt_connections_me_current 986
telemt_handshake_timeouts_total 5349
telemt_upstream_connect_attempt_total 3059
telemt_upstream_connect_success_total 3059
telemt_upstream_connect_attempts_per_request{bucket="1"} 3059
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1571
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1480
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 2215
telemt_me_reconnect_success_total 2205
telemt_me_reader_eof_total 2321
telemt_me_idle_close_by_peer_total 2321
telemt_me_route_drop_no_conn_total 100782
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 223123
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 578
telemt_desync_full_logged_total 215
telemt_desync_suppressed_total 363
telemt_desync_frames_bucket_total{bucket="1_2"} 112
telemt_desync_frames_bucket_total{bucket="3_10"} 234
telemt_desync_frames_bucket_total{bucket="gt_10"} 232
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2234
telemt_me_writer_restored_same_endpoint_total 2181
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 223034
telemt_user_connections_current{user="hello"} 986
telemt_user_octets_from_client{user="hello"} 2024935012 (1.89 GB)
telemt_user_octets_to_client{user="hello"} 76463421212 (71.21 GB)
telemt_user_unique_ips_current{user="hello"} 418
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 16507.6 (4h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 315792
telemt_connections_bad_total 18224
telemt_connections_current 1211
telemt_connections_me_current 1211
telemt_handshake_timeouts_total 10533
telemt_upstream_connect_attempt_total 3160
telemt_upstream_connect_success_total 3142
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 3160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1612
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 2299
telemt_me_reconnect_success_total 2286
telemt_me_reader_eof_total 2410
telemt_me_idle_close_by_peer_total 2410
telemt_me_route_drop_no_conn_total 96304
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 243533
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1010
telemt_desync_full_logged_total 380
telemt_desync_suppressed_total 630
telemt_desync_frames_bucket_total{bucket="1_2"} 276
telemt_desync_frames_bucket_total{bucket="3_10"} 373
telemt_desync_frames_bucket_total{bucket="gt_10"} 361
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2298
telemt_me_writer_restored_same_endpoint_total 2262
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 243456
telemt_user_connections_current{user="hello"} 1211
telemt_user_octets_from_client{user="hello"} 8203589308 (7.64 GB)
telemt_user_octets_to_client{user="hello"} 134073642080 (124.87 GB)
telemt_user_unique_ips_current{user="hello"} 536
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 16519.0 (4h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78695
telemt_connections_bad_total 9331
telemt_connections_current 329
telemt_connections_me_current 329
telemt_handshake_timeouts_total 333
telemt_upstream_connect_attempt_total 4855
telemt_upstream_connect_success_total 4713
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 4855
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2478
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_reconnect_attempts_total 5698
telemt_me_reconnect_success_total 3865
telemt_me_reader_eof_total 4046
telemt_me_idle_close_by_peer_total 4046
telemt_me_route_drop_no_conn_total 31405
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66656
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 30
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 3917
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 3835
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 66655
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 1515165068 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 49048876332 (45.68 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 16510.0 (4h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 223317
telemt_connections_bad_total 23721
telemt_connections_current 1087
telemt_connections_me_current 1087
telemt_handshake_timeouts_total 10949
telemt_upstream_connect_attempt_total 3560
telemt_upstream_connect_success_total 3560
telemt_upstream_connect_attempts_per_request{bucket="1"} 3560
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1880
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1678
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 2716
telemt_me_reconnect_success_total 2707
telemt_me_reader_eof_total 2850
telemt_me_idle_close_by_peer_total 2850
telemt_me_route_drop_no_conn_total 65664
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 183293
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1069
telemt_desync_full_logged_total 415
telemt_desync_suppressed_total 654
telemt_desync_frames_bucket_total{bucket="1_2"} 196
telemt_desync_frames_bucket_total{bucket="3_10"} 433
telemt_desync_frames_bucket_total{bucket="gt_10"} 440
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2739
telemt_me_writer_restored_same_endpoint_total 2692
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 183317
telemt_user_connections_current{user="hello"} 1087
telemt_user_octets_from_client{user="hello"} 1905723840 (1.77 GB)
telemt_user_octets_to_client{user="hello"} 94241192132 (87.77 GB)
telemt_user_unique_ips_current{user="hello"} 453
telemt_user_unique_ips_recent_window{user="hello"} 97
```