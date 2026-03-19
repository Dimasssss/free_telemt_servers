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

# Server Metrics 2026-03-19 07:50:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 36132.8 (10h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 646134
telemt_connections_bad_total 67105
telemt_connections_current 1507
telemt_connections_me_current 1507
telemt_handshake_timeouts_total 24097
telemt_upstream_connect_attempt_total 6917
telemt_upstream_connect_success_total 6790
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 6917
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3491
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 6112
telemt_me_reconnect_success_total 4962
telemt_me_reader_eof_total 5270
telemt_me_idle_close_by_peer_total 5269
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 183228
telemt_me_route_drop_channel_closed_total 63
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 489611
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3311
telemt_desync_full_logged_total 936
telemt_desync_suppressed_total 2375
telemt_desync_frames_bucket_total{bucket="1_2"} 1177
telemt_desync_frames_bucket_total{bucket="3_10"} 1237
telemt_desync_frames_bucket_total{bucket="gt_10"} 897
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 5054
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 4945
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 486720
telemt_user_connections_current{user="hello"} 1507
telemt_user_octets_from_client{user="hello"} 6329646452 (5.89 GB)
telemt_user_octets_to_client{user="hello"} 162853062324 (151.67 GB)
telemt_user_unique_ips_current{user="hello"} 500
telemt_user_unique_ips_recent_window{user="hello"} 243
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 36136.5 (10h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1538512
telemt_connections_bad_total 84741
telemt_connections_current 3909
telemt_connections_me_current 3909
telemt_handshake_timeouts_total 37033
telemt_upstream_connect_attempt_total 6798
telemt_upstream_connect_success_total 6668
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 6798
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3307
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3344
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 5980
telemt_me_reconnect_success_total 4824
telemt_me_reader_eof_total 5118
telemt_me_idle_close_by_peer_total 5118
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 634435
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1266680
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5713
telemt_desync_full_logged_total 1907
telemt_desync_suppressed_total 3806
telemt_desync_frames_bucket_total{bucket="1_2"} 1013
telemt_desync_frames_bucket_total{bucket="3_10"} 2172
telemt_desync_frames_bucket_total{bucket="gt_10"} 2528
telemt_pool_swap_total 29
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 4951
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 4803
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 1266586
telemt_user_connections_current{user="hello"} 3909
telemt_user_octets_from_client{user="hello"} 22928202200 (21.35 GB)
telemt_user_octets_to_client{user="hello"} 500171404968 (465.82 GB)
telemt_user_unique_ips_current{user="hello"} 1366
telemt_user_unique_ips_recent_window{user="hello"} 628
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 36133.9 (10h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1313102
telemt_connections_bad_total 184614
telemt_connections_current 3122
telemt_connections_me_current 3122
telemt_handshake_timeouts_total 34939
telemt_upstream_connect_attempt_total 6461
telemt_upstream_connect_success_total 6461
telemt_upstream_connect_attempts_per_request{bucket="1"} 6461
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3337
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3114
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 4648
telemt_me_reconnect_success_total 4623
telemt_me_reader_eof_total 4899
telemt_me_idle_close_by_peer_total 4899
telemt_me_route_drop_no_conn_total 551292
telemt_me_route_drop_channel_closed_total 46
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 989736
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4675
telemt_desync_full_logged_total 1448
telemt_desync_suppressed_total 3227
telemt_desync_frames_bucket_total{bucket="1_2"} 994
telemt_desync_frames_bucket_total{bucket="3_10"} 1675
telemt_desync_frames_bucket_total{bucket="gt_10"} 2006
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 4710
telemt_me_writer_restored_same_endpoint_total 4607
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 989339
telemt_user_connections_current{user="hello"} 3122
telemt_user_octets_from_client{user="hello"} 17625557580 (16.42 GB)
telemt_user_octets_to_client{user="hello"} 500290302196 (465.93 GB)
telemt_user_unique_ips_current{user="hello"} 1037
telemt_user_unique_ips_recent_window{user="hello"} 496
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 36186.5 (10h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1349690
telemt_connections_bad_total 90351
telemt_connections_current 2941
telemt_connections_me_current 2941
telemt_handshake_timeouts_total 33055
telemt_upstream_connect_attempt_total 6388
telemt_upstream_connect_success_total 6388
telemt_upstream_connect_attempts_per_request{bucket="1"} 6388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3237
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3135
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5596
telemt_me_reconnect_success_total 4534
telemt_me_reader_eof_total 4810
telemt_me_idle_close_by_peer_total 4809
telemt_me_route_drop_no_conn_total 510100
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 935043
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3546
telemt_desync_full_logged_total 1215
telemt_desync_suppressed_total 2331
telemt_desync_frames_bucket_total{bucket="1_2"} 690
telemt_desync_frames_bucket_total{bucket="3_10"} 1391
telemt_desync_frames_bucket_total{bucket="gt_10"} 1465
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 4632
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 4510
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 933827
telemt_user_connections_current{user="hello"} 2941
telemt_user_octets_from_client{user="hello"} 12938085316 (12.05 GB)
telemt_user_octets_to_client{user="hello"} 323057041972 (300.87 GB)
telemt_user_unique_ips_current{user="hello"} 990
telemt_user_unique_ips_recent_window{user="hello"} 455
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 36129.9 (10h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1627690
telemt_connections_bad_total 432202
telemt_connections_current 3378
telemt_connections_me_current 3378
telemt_handshake_timeouts_total 34845
telemt_upstream_connect_attempt_total 6319
telemt_upstream_connect_success_total 6278
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 6319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3181
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3076
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_reconnect_attempts_total 4477
telemt_me_reconnect_success_total 4444
telemt_me_reader_eof_total 4709
telemt_me_idle_close_by_peer_total 4709
telemt_me_route_drop_no_conn_total 410580
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 988433
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4756
telemt_desync_full_logged_total 1477
telemt_desync_suppressed_total 3279
telemt_desync_frames_bucket_total{bucket="1_2"} 1030
telemt_desync_frames_bucket_total{bucket="3_10"} 2163
telemt_desync_frames_bucket_total{bucket="gt_10"} 1563
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 4502
telemt_me_writer_restored_same_endpoint_total 4420
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 988107
telemt_user_connections_current{user="hello"} 3378
telemt_user_octets_from_client{user="hello"} 20642222428 (19.22 GB)
telemt_user_octets_to_client{user="hello"} 477191360468 (444.42 GB)
telemt_user_unique_ips_current{user="hello"} 1126
telemt_user_unique_ips_recent_window{user="hello"} 533
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 36142.0 (10h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 275158
telemt_connections_bad_total 13128
telemt_connections_current 868
telemt_connections_me_current 868
telemt_handshake_timeouts_total 2644
telemt_upstream_connect_attempt_total 9435
telemt_upstream_connect_success_total 9189
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 9435
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4670
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 12728
telemt_me_reconnect_success_total 7351
telemt_me_reader_eof_total 7810
telemt_me_idle_close_by_peer_total 7810
telemt_me_route_drop_no_conn_total 128896
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 245265
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 373
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 248
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 156
telemt_desync_frames_bucket_total{bucket="gt_10"} 107
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 7568
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 7321
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 217
telemt_user_connections_total{user="hello"} 245237
telemt_user_connections_current{user="hello"} 868
telemt_user_octets_from_client{user="hello"} 3648211788 (3.40 GB)
telemt_user_octets_to_client{user="hello"} 117290335112 (109.24 GB)
telemt_user_unique_ips_current{user="hello"} 312
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 36132.5 (10h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1039435
telemt_connections_bad_total 94097
telemt_connections_current 3001
telemt_connections_me_current 3001
telemt_handshake_timeouts_total 46695
telemt_upstream_connect_attempt_total 7299
telemt_upstream_connect_success_total 7299
telemt_upstream_connect_attempts_per_request{bucket="1"} 7299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3404
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 6800
telemt_me_reconnect_success_total 5465
telemt_me_reader_eof_total 5804
telemt_me_idle_close_by_peer_total 5804
telemt_me_route_drop_no_conn_total 412305
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 858904
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5150
telemt_desync_full_logged_total 1700
telemt_desync_suppressed_total 3450
telemt_desync_frames_bucket_total{bucket="1_2"} 1023
telemt_desync_frames_bucket_total{bucket="3_10"} 1971
telemt_desync_frames_bucket_total{bucket="gt_10"} 2156
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 5568
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 5450
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 857969
telemt_user_connections_current{user="hello"} 3001
telemt_user_octets_from_client{user="hello"} 12718320212 (11.84 GB)
telemt_user_octets_to_client{user="hello"} 460594720840 (428.96 GB)
telemt_user_unique_ips_current{user="hello"} 985
telemt_user_unique_ips_recent_window{user="hello"} 420
```