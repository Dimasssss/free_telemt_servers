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

# Server Metrics 2026-03-19 08:06:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 37053.1 (10h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 677889
telemt_connections_bad_total 70129
telemt_connections_current 1482
telemt_connections_me_current 1482
telemt_handshake_timeouts_total 24926
telemt_upstream_connect_attempt_total 7035
telemt_upstream_connect_success_total 6905
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 7035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3350
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3552
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 6182
telemt_me_reconnect_success_total 5029
telemt_me_reader_eof_total 5341
telemt_me_idle_close_by_peer_total 5340
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 193152
telemt_me_route_drop_channel_closed_total 69
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 516054
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3419
telemt_desync_full_logged_total 976
telemt_desync_suppressed_total 2443
telemt_desync_frames_bucket_total{bucket="1_2"} 1196
telemt_desync_frames_bucket_total{bucket="3_10"} 1277
telemt_desync_frames_bucket_total{bucket="gt_10"} 946
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 5124
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 5012
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 513094
telemt_user_connections_current{user="hello"} 1482
telemt_user_octets_from_client{user="hello"} 6921764896 (6.45 GB)
telemt_user_octets_to_client{user="hello"} 170113715352 (158.43 GB)
telemt_user_unique_ips_current{user="hello"} 553
telemt_user_unique_ips_recent_window{user="hello"} 253
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 37057.1 (10h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1637312
telemt_connections_bad_total 93635
telemt_connections_current 3867
telemt_connections_me_current 3867
telemt_handshake_timeouts_total 39256
telemt_upstream_connect_attempt_total 7046
telemt_upstream_connect_success_total 6913
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 7046
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3428
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3466
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 6179
telemt_me_reconnect_success_total 5022
telemt_me_reader_eof_total 5316
telemt_me_idle_close_by_peer_total 5316
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 714435
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1348486
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6044
telemt_desync_full_logged_total 2023
telemt_desync_suppressed_total 4021
telemt_desync_frames_bucket_total{bucket="1_2"} 1060
telemt_desync_frames_bucket_total{bucket="3_10"} 2299
telemt_desync_frames_bucket_total{bucket="gt_10"} 2685
telemt_pool_swap_total 30
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 5149
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 5001
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 1348290
telemt_user_connections_current{user="hello"} 3867
telemt_user_octets_from_client{user="hello"} 23679988520 (22.05 GB)
telemt_user_octets_to_client{user="hello"} 522359990680 (486.49 GB)
telemt_user_unique_ips_current{user="hello"} 1380
telemt_user_unique_ips_recent_window{user="hello"} 728
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 37054.6 (10h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1395761
telemt_connections_bad_total 187873
telemt_connections_current 3628
telemt_connections_me_current 3628
telemt_handshake_timeouts_total 36199
telemt_upstream_connect_attempt_total 6610
telemt_upstream_connect_success_total 6610
telemt_upstream_connect_attempts_per_request{bucket="1"} 6610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3167
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 4757
telemt_me_reconnect_success_total 4732
telemt_me_reader_eof_total 5014
telemt_me_idle_close_by_peer_total 5014
telemt_me_route_drop_no_conn_total 637184
telemt_me_route_drop_channel_closed_total 47
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1062520
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4945
telemt_desync_full_logged_total 1521
telemt_desync_suppressed_total 3424
telemt_desync_frames_bucket_total{bucket="1_2"} 1067
telemt_desync_frames_bucket_total{bucket="3_10"} 1777
telemt_desync_frames_bucket_total{bucket="gt_10"} 2101
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 4820
telemt_me_writer_restored_same_endpoint_total 4716
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 1062115
telemt_user_connections_current{user="hello"} 3628
telemt_user_octets_from_client{user="hello"} 18243925044 (16.99 GB)
telemt_user_octets_to_client{user="hello"} 528877276120 (492.56 GB)
telemt_user_unique_ips_current{user="hello"} 1163
telemt_user_unique_ips_recent_window{user="hello"} 763
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 37107.5 (10h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1415771
telemt_connections_bad_total 92450
telemt_connections_current 3395
telemt_connections_me_current 3395
telemt_handshake_timeouts_total 35375
telemt_upstream_connect_attempt_total 6654
telemt_upstream_connect_success_total 6654
telemt_upstream_connect_attempts_per_request{bucket="1"} 6654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3368
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3269
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6134
telemt_me_reconnect_success_total 4737
telemt_me_reader_eof_total 5022
telemt_me_idle_close_by_peer_total 5021
telemt_me_route_drop_no_conn_total 563748
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 992897
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3708
telemt_desync_full_logged_total 1274
telemt_desync_suppressed_total 2434
telemt_desync_frames_bucket_total{bucket="1_2"} 728
telemt_desync_frames_bucket_total{bucket="3_10"} 1454
telemt_desync_frames_bucket_total{bucket="gt_10"} 1526
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 4846
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 4713
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 991652
telemt_user_connections_current{user="hello"} 3395
telemt_user_octets_from_client{user="hello"} 13636617260 (12.70 GB)
telemt_user_octets_to_client{user="hello"} 338481600336 (315.24 GB)
telemt_user_unique_ips_current{user="hello"} 1029
telemt_user_unique_ips_recent_window{user="hello"} 538
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 37050.9 (10h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1710293
telemt_connections_bad_total 444197
telemt_connections_current 3547
telemt_connections_me_current 3547
telemt_handshake_timeouts_total 36114
telemt_upstream_connect_attempt_total 6413
telemt_upstream_connect_success_total 6369
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 6413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3120
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_reconnect_attempts_total 4542
telemt_me_reconnect_success_total 4509
telemt_me_reader_eof_total 4780
telemt_me_idle_close_by_peer_total 4780
telemt_me_route_drop_no_conn_total 437573
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1050880
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5101
telemt_desync_full_logged_total 1578
telemt_desync_suppressed_total 3523
telemt_desync_frames_bucket_total{bucket="1_2"} 1072
telemt_desync_frames_bucket_total{bucket="3_10"} 2317
telemt_desync_frames_bucket_total{bucket="gt_10"} 1712
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 4569
telemt_me_writer_restored_same_endpoint_total 4485
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 1050530
telemt_user_connections_current{user="hello"} 3547
telemt_user_octets_from_client{user="hello"} 21520664796 (20.04 GB)
telemt_user_octets_to_client{user="hello"} 500169562284 (465.82 GB)
telemt_user_unique_ips_current{user="hello"} 1153
telemt_user_unique_ips_recent_window{user="hello"} 581
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 37063.5 (10h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 292533
telemt_connections_bad_total 14619
telemt_connections_current 920
telemt_connections_me_current 920
telemt_handshake_timeouts_total 2726
telemt_upstream_connect_attempt_total 9596
telemt_upstream_connect_success_total 9349
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 9595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4750
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 12844
telemt_me_reconnect_success_total 7467
telemt_me_reader_eof_total 7935
telemt_me_idle_close_by_peer_total 7935
telemt_me_route_drop_no_conn_total 135518
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 260396
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 390
telemt_desync_full_logged_total 130
telemt_desync_suppressed_total 260
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 162
telemt_desync_frames_bucket_total{bucket="gt_10"} 114
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 7685
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 7437
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 260361
telemt_user_connections_current{user="hello"} 920
telemt_user_octets_from_client{user="hello"} 3873481884 (3.61 GB)
telemt_user_octets_to_client{user="hello"} 121301234552 (112.97 GB)
telemt_user_unique_ips_current{user="hello"} 314
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 37053.3 (10h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1114141
telemt_connections_bad_total 96713
telemt_connections_current 3234
telemt_connections_me_current 3234
telemt_handshake_timeouts_total 49390
telemt_upstream_connect_attempt_total 7448
telemt_upstream_connect_success_total 7447
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3961
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3483
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 6913
telemt_me_reconnect_success_total 5575
telemt_me_reader_eof_total 5918
telemt_me_idle_close_by_peer_total 5917
telemt_me_route_drop_no_conn_total 441654
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 925944
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5482
telemt_desync_full_logged_total 1811
telemt_desync_suppressed_total 3671
telemt_desync_frames_bucket_total{bucket="1_2"} 1078
telemt_desync_frames_bucket_total{bucket="3_10"} 2075
telemt_desync_frames_bucket_total{bucket="gt_10"} 2329
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 5679
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 5560
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 924938
telemt_user_connections_current{user="hello"} 3234
telemt_user_octets_from_client{user="hello"} 13210662312 (12.30 GB)
telemt_user_octets_to_client{user="hello"} 480554130128 (447.55 GB)
telemt_user_unique_ips_current{user="hello"} 1022
telemt_user_unique_ips_recent_window{user="hello"} 435
```