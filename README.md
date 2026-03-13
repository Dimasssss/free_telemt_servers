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

# Server Metrics 2026-03-13 16:01:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 116877.0 (32h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 485509
telemt_connections_bad_total 3519
telemt_handshake_timeouts_total 8882
telemt_upstream_connect_attempt_total 29135
telemt_upstream_connect_success_total 28995
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 29135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15836
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2507
telemt_me_reconnect_attempts_total 26699
telemt_me_reconnect_success_total 23163
telemt_me_reader_eof_total 24744
telemt_me_idle_close_by_peer_total 24743
telemt_me_route_drop_no_conn_total 158797
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 426409
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1380
telemt_desync_full_logged_total 485
telemt_desync_suppressed_total 895
telemt_desync_frames_bucket_total{bucket="1_2"} 302
telemt_desync_frames_bucket_total{bucket="3_10"} 495
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 23518
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 23147
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 355
telemt_user_connections_total{user="hello"} 425986
telemt_user_connections_current{user="hello"} 322
telemt_user_octets_from_client{user="hello"} 7570204764 (7.05 GB)
telemt_user_octets_to_client{user="hello"} 199025315264 (185.36 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 116771.4 (32h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 234834
telemt_connections_bad_total 1840
telemt_handshake_timeouts_total 1690
telemt_upstream_connect_attempt_total 91442
telemt_upstream_connect_success_total 90652
telemt_upstream_connect_fail_total 789
telemt_upstream_connect_attempts_per_request{bucket="1"} 91441
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65085
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24470
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1097
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 789
telemt_me_keepalive_timeout_total 1417
telemt_me_reconnect_attempts_total 116309
telemt_me_reconnect_success_total 26024
telemt_me_reader_eof_total 29602
telemt_me_idle_close_by_peer_total 29602
telemt_me_route_drop_no_conn_total 81712
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163605
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 29069
telemt_me_refill_failed_total 2817
telemt_me_writer_restored_same_endpoint_total 26007
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3045
telemt_user_connections_total{user="hello"} 222194
telemt_user_connections_current{user="hello"} 249
telemt_user_octets_from_client{user="hello"} 2306816040 (2.15 GB)
telemt_user_octets_to_client{user="hello"} 69561127548 (64.78 GB)
telemt_user_msgs_from_client{user="hello"} 906960
telemt_user_msgs_to_client{user="hello"} 5514423
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 116735.7 (32h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 282124
telemt_connections_bad_total 2441
telemt_handshake_timeouts_total 13648
telemt_upstream_connect_attempt_total 31248
telemt_upstream_connect_success_total 31244
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 31248
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16729
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2408
telemt_me_reconnect_attempts_total 26592
telemt_me_reconnect_success_total 25371
telemt_me_reader_eof_total 27196
telemt_me_idle_close_by_peer_total 27196
telemt_me_route_drop_no_conn_total 101819
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 256027
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 103
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 25653
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 25351
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 282
telemt_user_connections_total{user="hello"} 255942
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 9675909972 (9.01 GB)
telemt_user_octets_to_client{user="hello"} 108182222496 (100.75 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 116709.8 (32h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 382834
telemt_connections_bad_total 15062
telemt_handshake_timeouts_total 3780
telemt_upstream_connect_attempt_total 43134
telemt_upstream_connect_success_total 32952
telemt_upstream_connect_fail_total 10182
telemt_upstream_connect_attempts_per_request{bucket="1"} 43134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16157
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10182
telemt_me_keepalive_timeout_total 4168
telemt_me_reconnect_attempts_total 105526
telemt_me_reconnect_success_total 24077
telemt_me_reader_eof_total 27330
telemt_me_idle_close_by_peer_total 27323
telemt_me_route_drop_no_conn_total 137157
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 332262
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1345
telemt_desync_full_logged_total 398
telemt_desync_suppressed_total 947
telemt_desync_frames_bucket_total{bucket="1_2"} 331
telemt_desync_frames_bucket_total{bucket="3_10"} 515
telemt_desync_frames_bucket_total{bucket="gt_10"} 499
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 26929
telemt_me_refill_failed_total 2540
telemt_me_writer_restored_same_endpoint_total 24067
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2852
telemt_user_connections_total{user="hello"} 335173
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 6960714722 (6.48 GB)
telemt_user_octets_to_client{user="hello"} 124458181593 (115.91 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 66881.5 (18h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105221
telemt_connections_bad_total 13539
telemt_handshake_timeouts_total 1325
telemt_upstream_connect_attempt_total 26989
telemt_upstream_connect_success_total 26752
telemt_upstream_connect_fail_total 237
telemt_upstream_connect_attempts_per_request{bucket="1"} 26989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12744
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 237
telemt_me_keepalive_timeout_total 1057
telemt_me_reconnect_attempts_total 29661
telemt_me_reconnect_success_total 18488
telemt_me_reader_eof_total 19821
telemt_me_idle_close_by_peer_total 19821
telemt_me_route_drop_no_conn_total 32353
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 82041
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 390
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 18994
telemt_me_refill_failed_total 347
telemt_me_writer_restored_same_endpoint_total 18470
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 506
telemt_user_connections_total{user="hello"} 86940
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 1005049273 (958.49 MB)
telemt_user_octets_to_client{user="hello"} 26571992163 (24.75 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 116667.1 (32h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 707773
telemt_connections_bad_total 24529
telemt_handshake_timeouts_total 23506
telemt_upstream_connect_attempt_total 24425
telemt_upstream_connect_success_total 24303
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 24425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12875
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_timeout_total 2557
telemt_me_reconnect_attempts_total 23137
telemt_me_reconnect_success_total 18508
telemt_me_reader_eof_total 19861
telemt_me_idle_close_by_peer_total 19858
telemt_me_route_drop_no_conn_total 334367
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 663589
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 666
telemt_desync_full_logged_total 216
telemt_desync_suppressed_total 450
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 220
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 18888
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 18501
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 380
telemt_user_connections_total{user="hello"} 636493
telemt_user_connections_current{user="hello"} 455
telemt_user_octets_from_client{user="hello"} 11074664596 (10.31 GB)
telemt_user_octets_to_client{user="hello"} 327308130672 (304.83 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 70
```