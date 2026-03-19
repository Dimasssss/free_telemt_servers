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

# Server Metrics 2026-03-19 04:46:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 25097.0 (6h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 348454
telemt_connections_bad_total 36385
telemt_connections_current 1036
telemt_connections_me_current 1036
telemt_handshake_timeouts_total 20000
telemt_upstream_connect_attempt_total 4895
telemt_upstream_connect_success_total 4815
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 4895
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3587
telemt_me_reconnect_success_total 3570
telemt_me_reader_eof_total 3759
telemt_me_idle_close_by_peer_total 3758
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 89669
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 255401
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1791
telemt_desync_full_logged_total 490
telemt_desync_suppressed_total 1301
telemt_desync_frames_bucket_total{bucket="1_2"} 667
telemt_desync_frames_bucket_total{bucket="3_10"} 723
telemt_desync_frames_bucket_total{bucket="gt_10"} 401
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 3598
telemt_me_writer_restored_same_endpoint_total 3553
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 252662
telemt_user_connections_current{user="hello"} 1036
telemt_user_octets_from_client{user="hello"} 2900084588 (2.70 GB)
telemt_user_octets_to_client{user="hello"} 77089041332 (71.79 GB)
telemt_user_unique_ips_current{user="hello"} 376
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 25100.8 (6h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 654282
telemt_connections_bad_total 39989
telemt_connections_current 2649
telemt_connections_me_current 2649
telemt_handshake_timeouts_total 19580
telemt_upstream_connect_attempt_total 4709
telemt_upstream_connect_success_total 4624
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 4709
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2224
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2390
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_reconnect_attempts_total 3388
telemt_me_reconnect_success_total 3371
telemt_me_reader_eof_total 3554
telemt_me_idle_close_by_peer_total 3554
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 197393
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 542635
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2128
telemt_desync_full_logged_total 719
telemt_desync_suppressed_total 1409
telemt_desync_frames_bucket_total{bucket="1_2"} 428
telemt_desync_frames_bucket_total{bucket="3_10"} 783
telemt_desync_frames_bucket_total{bucket="gt_10"} 917
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 3430
telemt_me_writer_restored_same_endpoint_total 3353
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 542569
telemt_user_connections_current{user="hello"} 2649
telemt_user_octets_from_client{user="hello"} 14954200280 (13.93 GB)
telemt_user_octets_to_client{user="hello"} 238306375888 (221.94 GB)
telemt_user_unique_ips_current{user="hello"} 966
telemt_user_unique_ips_recent_window{user="hello"} 348
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 25098.6 (6h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 554554
telemt_connections_bad_total 107476
telemt_connections_current 2326
telemt_connections_me_current 2326
telemt_handshake_timeouts_total 18788
telemt_upstream_connect_attempt_total 4598
telemt_upstream_connect_success_total 4598
telemt_upstream_connect_attempts_per_request{bucket="1"} 4598
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2259
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3358
telemt_me_reconnect_success_total 3347
telemt_me_reader_eof_total 3543
telemt_me_idle_close_by_peer_total 3543
telemt_me_route_drop_no_conn_total 164362
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 398174
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2140
telemt_desync_full_logged_total 708
telemt_desync_suppressed_total 1432
telemt_desync_frames_bucket_total{bucket="1_2"} 328
telemt_desync_frames_bucket_total{bucket="3_10"} 761
telemt_desync_frames_bucket_total{bucket="gt_10"} 1051
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 3402
telemt_me_writer_restored_same_endpoint_total 3331
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 398155
telemt_user_connections_current{user="hello"} 2326
telemt_user_octets_from_client{user="hello"} 8811694660 (8.21 GB)
telemt_user_octets_to_client{user="hello"} 251784581280 (234.49 GB)
telemt_user_unique_ips_current{user="hello"} 782
telemt_user_unique_ips_recent_window{user="hello"} 261
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 25151.4 (6h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 656962
telemt_connections_bad_total 84948
telemt_connections_current 1633
telemt_connections_me_current 1633
telemt_handshake_timeouts_total 14282
telemt_upstream_connect_attempt_total 4461
telemt_upstream_connect_success_total 4461
telemt_upstream_connect_attempts_per_request{bucket="1"} 4461
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2251
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2201
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 3227
telemt_me_reconnect_success_total 3213
telemt_me_reader_eof_total 3388
telemt_me_idle_close_by_peer_total 3387
telemt_me_route_drop_no_conn_total 163347
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 393220
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1213
telemt_desync_full_logged_total 439
telemt_desync_suppressed_total 774
telemt_desync_frames_bucket_total{bucket="1_2"} 230
telemt_desync_frames_bucket_total{bucket="3_10"} 517
telemt_desync_frames_bucket_total{bucket="gt_10"} 466
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 3251
telemt_me_writer_restored_same_endpoint_total 3189
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 392986
telemt_user_connections_current{user="hello"} 1633
telemt_user_octets_from_client{user="hello"} 4747990360 (4.42 GB)
telemt_user_octets_to_client{user="hello"} 152082857772 (141.64 GB)
telemt_user_unique_ips_current{user="hello"} 629
telemt_user_unique_ips_recent_window{user="hello"} 213
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 25094.7 (6h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 716662
telemt_connections_bad_total 191575
telemt_connections_current 1891
telemt_connections_me_current 1891
telemt_handshake_timeouts_total 20002
telemt_upstream_connect_attempt_total 4609
telemt_upstream_connect_success_total 4580
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 4609
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2270
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_reconnect_attempts_total 3344
telemt_me_reconnect_success_total 3324
telemt_me_reader_eof_total 3512
telemt_me_idle_close_by_peer_total 3512
telemt_me_route_drop_no_conn_total 178656
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 427890
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1898
telemt_desync_full_logged_total 722
telemt_desync_suppressed_total 1176
telemt_desync_frames_bucket_total{bucket="1_2"} 446
telemt_desync_frames_bucket_total{bucket="3_10"} 803
telemt_desync_frames_bucket_total{bucket="gt_10"} 649
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 3356
telemt_me_writer_restored_same_endpoint_total 3300
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 427804
telemt_user_connections_current{user="hello"} 1891
telemt_user_octets_from_client{user="hello"} 13281728884 (12.37 GB)
telemt_user_octets_to_client{user="hello"} 250912930928 (233.68 GB)
telemt_user_unique_ips_current{user="hello"} 752
telemt_user_unique_ips_recent_window{user="hello"} 244
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 25106.1 (6h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127963
telemt_connections_bad_total 10304
telemt_connections_current 528
telemt_connections_me_current 528
telemt_handshake_timeouts_total 586
telemt_upstream_connect_attempt_total 6882
telemt_upstream_connect_success_total 6699
telemt_upstream_connect_fail_total 183
telemt_upstream_connect_attempts_per_request{bucket="1"} 6882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3526
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 183
telemt_me_reconnect_attempts_total 7291
telemt_me_reconnect_success_total 5448
telemt_me_reader_eof_total 5727
telemt_me_idle_close_by_peer_total 5727
telemt_me_route_drop_no_conn_total 52108
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 112275
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 120
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 76
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 29
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 5522
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 5418
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 112267
telemt_user_connections_current{user="hello"} 528
telemt_user_octets_from_client{user="hello"} 2035944964 (1.90 GB)
telemt_user_octets_to_client{user="hello"} 71610608476 (66.69 GB)
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 25096.9 (6h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 422379
telemt_connections_bad_total 47267
telemt_connections_current 1870
telemt_connections_me_current 1870
telemt_handshake_timeouts_total 21877
telemt_upstream_connect_attempt_total 5172
telemt_upstream_connect_success_total 5172
telemt_upstream_connect_attempts_per_request{bucket="1"} 5172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2745
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2424
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 3937
telemt_me_reconnect_success_total 3925
telemt_me_reader_eof_total 4142
telemt_me_idle_close_by_peer_total 4142
telemt_me_route_drop_no_conn_total 118674
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 340294
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1790
telemt_desync_full_logged_total 681
telemt_desync_suppressed_total 1109
telemt_desync_frames_bucket_total{bucket="1_2"} 365
telemt_desync_frames_bucket_total{bucket="3_10"} 687
telemt_desync_frames_bucket_total{bucket="gt_10"} 738
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 3968
telemt_me_writer_restored_same_endpoint_total 3910
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 340308
telemt_user_connections_current{user="hello"} 1870
telemt_user_octets_from_client{user="hello"} 4208686772 (3.92 GB)
telemt_user_octets_to_client{user="hello"} 197800678720 (184.22 GB)
telemt_user_unique_ips_current{user="hello"} 649
telemt_user_unique_ips_recent_window{user="hello"} 238
```