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

# Server Metrics 2026-03-19 06:49:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 32452.1 (9h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 529993
telemt_connections_bad_total 57360
telemt_connections_current 1238
telemt_connections_me_current 1238
telemt_handshake_timeouts_total 22599
telemt_upstream_connect_attempt_total 6271
telemt_upstream_connect_success_total 6163
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 6271
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3155
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 5687
telemt_me_reconnect_success_total 4542
telemt_me_reader_eof_total 4813
telemt_me_idle_close_by_peer_total 4812
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 144447
telemt_me_route_drop_channel_closed_total 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 396065
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2483
telemt_desync_full_logged_total 722
telemt_desync_suppressed_total 1761
telemt_desync_frames_bucket_total{bucket="1_2"} 827
telemt_desync_frames_bucket_total{bucket="3_10"} 964
telemt_desync_frames_bucket_total{bucket="gt_10"} 692
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 4625
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 4525
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 393303
telemt_user_connections_current{user="hello"} 1238
telemt_user_octets_from_client{user="hello"} 5464658724 (5.09 GB)
telemt_user_octets_to_client{user="hello"} 133328487692 (124.17 GB)
telemt_user_unique_ips_current{user="hello"} 456
telemt_user_unique_ips_recent_window{user="hello"} 177
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 32456.2 (9h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1136893
telemt_connections_bad_total 63531
telemt_connections_current 3725
telemt_connections_me_current 3725
telemt_handshake_timeouts_total 29621
telemt_upstream_connect_attempt_total 6021
telemt_upstream_connect_success_total 5913
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 6021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2968
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_reconnect_attempts_total 5432
telemt_me_reconnect_success_total 4283
telemt_me_reader_eof_total 4552
telemt_me_idle_close_by_peer_total 4552
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 372673
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 941998
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4108
telemt_desync_full_logged_total 1412
telemt_desync_suppressed_total 2696
telemt_desync_frames_bucket_total{bucket="1_2"} 736
telemt_desync_frames_bucket_total{bucket="3_10"} 1557
telemt_desync_frames_bucket_total{bucket="gt_10"} 1815
telemt_pool_swap_total 28
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 4399
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 4263
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 941930
telemt_user_connections_current{user="hello"} 3725
telemt_user_octets_from_client{user="hello"} 19818045192 (18.46 GB)
telemt_user_octets_to_client{user="hello"} 413024845880 (384.66 GB)
telemt_user_unique_ips_current{user="hello"} 1303
telemt_user_unique_ips_recent_window{user="hello"} 552
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 32457.2 (9h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 986504
telemt_connections_bad_total 151523
telemt_connections_current 3025
telemt_connections_me_current 3025
telemt_handshake_timeouts_total 29316
telemt_upstream_connect_attempt_total 5869
telemt_upstream_connect_success_total 5869
telemt_upstream_connect_attempts_per_request{bucket="1"} 5869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2856
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 4257
telemt_me_reconnect_success_total 4238
telemt_me_reader_eof_total 4489
telemt_me_idle_close_by_peer_total 4489
telemt_me_route_drop_no_conn_total 309942
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 727341
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3551
telemt_desync_full_logged_total 1129
telemt_desync_suppressed_total 2422
telemt_desync_frames_bucket_total{bucket="1_2"} 661
telemt_desync_frames_bucket_total{bucket="3_10"} 1288
telemt_desync_frames_bucket_total{bucket="gt_10"} 1602
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 4316
telemt_me_writer_restored_same_endpoint_total 4222
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 727016
telemt_user_connections_current{user="hello"} 3025
telemt_user_octets_from_client{user="hello"} 13433811476 (12.51 GB)
telemt_user_octets_to_client{user="hello"} 403742160976 (376.01 GB)
telemt_user_unique_ips_current{user="hello"} 1033
telemt_user_unique_ips_recent_window{user="hello"} 438
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 32506.3 (9h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1040998
telemt_connections_bad_total 88621
telemt_connections_current 2815
telemt_connections_me_current 2815
telemt_handshake_timeouts_total 25504
telemt_upstream_connect_attempt_total 5713
telemt_upstream_connect_success_total 5713
telemt_upstream_connect_attempts_per_request{bucket="1"} 5713
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2808
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 5107
telemt_me_reconnect_success_total 4056
telemt_me_reader_eof_total 4311
telemt_me_idle_close_by_peer_total 4310
telemt_me_route_drop_no_conn_total 353369
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 717104
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2722
telemt_desync_full_logged_total 971
telemt_desync_suppressed_total 1751
telemt_desync_frames_bucket_total{bucket="1_2"} 492
telemt_desync_frames_bucket_total{bucket="3_10"} 1083
telemt_desync_frames_bucket_total{bucket="gt_10"} 1147
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 4147
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 4032
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 715987
telemt_user_connections_current{user="hello"} 2815
telemt_user_octets_from_client{user="hello"} 10985010104 (10.23 GB)
telemt_user_octets_to_client{user="hello"} 266811496340 (248.49 GB)
telemt_user_unique_ips_current{user="hello"} 968
telemt_user_unique_ips_recent_window{user="hello"} 412
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 32449.7 (9h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1280432
telemt_connections_bad_total 362124
telemt_connections_current 2943
telemt_connections_me_current 2943
telemt_handshake_timeouts_total 30237
telemt_upstream_connect_attempt_total 5714
telemt_upstream_connect_success_total 5679
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 5714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2869
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2791
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_reconnect_attempts_total 4087
telemt_me_reconnect_success_total 4058
telemt_me_reader_eof_total 4297
telemt_me_idle_close_by_peer_total 4297
telemt_me_route_drop_no_conn_total 313296
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 761648
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3777
telemt_desync_full_logged_total 1209
telemt_desync_suppressed_total 2568
telemt_desync_frames_bucket_total{bucket="1_2"} 842
telemt_desync_frames_bucket_total{bucket="3_10"} 1682
telemt_desync_frames_bucket_total{bucket="gt_10"} 1253
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 4106
telemt_me_writer_restored_same_endpoint_total 4034
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 761445
telemt_user_connections_current{user="hello"} 2943
telemt_user_octets_from_client{user="hello"} 17697859152 (16.48 GB)
telemt_user_octets_to_client{user="hello"} 394514982548 (367.42 GB)
telemt_user_unique_ips_current{user="hello"} 1058
telemt_user_unique_ips_recent_window{user="hello"} 461
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 32461.8 (9h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 212106
telemt_connections_bad_total 12298
telemt_connections_current 773
telemt_connections_me_current 773
telemt_handshake_timeouts_total 1782
telemt_upstream_connect_attempt_total 8589
telemt_upstream_connect_success_total 8372
telemt_upstream_connect_fail_total 217
telemt_upstream_connect_attempts_per_request{bucket="1"} 8589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4090
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4282
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 217
telemt_me_reconnect_attempts_total 11199
telemt_me_reconnect_success_total 6759
telemt_me_reader_eof_total 7156
telemt_me_idle_close_by_peer_total 7156
telemt_me_route_drop_no_conn_total 87906
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 186693
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 298
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 191
telemt_desync_frames_bucket_total{bucket="1_2"} 76
telemt_desync_frames_bucket_total{bucket="3_10"} 134
telemt_desync_frames_bucket_total{bucket="gt_10"} 88
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 6931
telemt_me_refill_failed_total 138
telemt_me_writer_restored_same_endpoint_total 6729
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 186681
telemt_user_connections_current{user="hello"} 773
telemt_user_octets_from_client{user="hello"} 2971388164 (2.77 GB)
telemt_user_octets_to_client{user="hello"} 98236641748 (91.49 GB)
telemt_user_unique_ips_current{user="hello"} 295
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 32452.3 (9h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 789125
telemt_connections_bad_total 87329
telemt_connections_current 3111
telemt_connections_me_current 3111
telemt_handshake_timeouts_total 34397
telemt_upstream_connect_attempt_total 6494
telemt_upstream_connect_success_total 6494
telemt_upstream_connect_attempts_per_request{bucket="1"} 6494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3036
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 4894
telemt_me_reconnect_success_total 4880
telemt_me_reader_eof_total 5150
telemt_me_idle_close_by_peer_total 5150
telemt_me_route_drop_no_conn_total 273200
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 638073
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3604
telemt_desync_full_logged_total 1273
telemt_desync_suppressed_total 2331
telemt_desync_frames_bucket_total{bucket="1_2"} 696
telemt_desync_frames_bucket_total{bucket="3_10"} 1391
telemt_desync_frames_bucket_total{bucket="gt_10"} 1517
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 4933
telemt_me_writer_restored_same_endpoint_total 4865
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 637863
telemt_user_connections_current{user="hello"} 3111
telemt_user_octets_from_client{user="hello"} 9507201768 (8.85 GB)
telemt_user_octets_to_client{user="hello"} 365669709328 (340.56 GB)
telemt_user_unique_ips_current{user="hello"} 953
telemt_user_unique_ips_recent_window{user="hello"} 417
```