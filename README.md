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

# Server Metrics 2026-03-13 17:22:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 121768.3 (33h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 512939
telemt_connections_bad_total 6926
telemt_handshake_timeouts_total 11669
telemt_upstream_connect_attempt_total 30344
telemt_upstream_connect_success_total 30193
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 30344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13686
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16434
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3385
telemt_me_reconnect_attempts_total 27636
telemt_me_reconnect_success_total 24086
telemt_me_reader_eof_total 25711
telemt_me_idle_close_by_peer_total 25710
telemt_me_route_drop_no_conn_total 166904
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 446618
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1442
telemt_desync_full_logged_total 502
telemt_desync_suppressed_total 940
telemt_desync_frames_bucket_total{bucket="1_2"} 318
telemt_desync_frames_bucket_total{bucket="3_10"} 522
telemt_desync_frames_bucket_total{bucket="gt_10"} 602
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 24459
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 24070
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 373
telemt_user_connections_total{user="hello"} 446187
telemt_user_connections_current{user="hello"} 380
telemt_user_octets_from_client{user="hello"} 8151124608 (7.59 GB)
telemt_user_octets_to_client{user="hello"} 208509514872 (194.19 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 121661.9 (33h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 251691
telemt_connections_bad_total 1944
telemt_handshake_timeouts_total 1808
telemt_upstream_connect_attempt_total 105982
telemt_upstream_connect_success_total 105150
telemt_upstream_connect_fail_total 832
telemt_upstream_connect_attempts_per_request{bucket="1"} 105982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 77688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25979
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1483
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 832
telemt_me_keepalive_timeout_total 1502
telemt_me_reconnect_attempts_total 123840
telemt_me_reconnect_success_total 26033
telemt_me_reader_eof_total 29843
telemt_me_idle_close_by_peer_total 29843
telemt_me_route_drop_no_conn_total 82353
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165453
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 30
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
telemt_me_writer_removed_unexpected_total 29313
telemt_me_refill_failed_total 3052
telemt_me_writer_restored_same_endpoint_total 26016
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3280
telemt_user_connections_total{user="hello"} 238263
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 2486182287 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 73515768280 (68.47 GB)
telemt_user_msgs_from_client{user="hello"} 1144165
telemt_user_msgs_to_client{user="hello"} 6669063
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 121625.7 (33h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 297787
telemt_connections_bad_total 2474
telemt_handshake_timeouts_total 16232
telemt_upstream_connect_attempt_total 32496
telemt_upstream_connect_success_total 32492
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 32496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15083
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17377
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2582
telemt_me_reconnect_attempts_total 27578
telemt_me_reconnect_success_total 26352
telemt_me_reader_eof_total 28247
telemt_me_idle_close_by_peer_total 28247
telemt_me_route_drop_no_conn_total 106613
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 268579
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 104
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 26646
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 26332
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 294
telemt_user_connections_total{user="hello"} 268487
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 10140442836 (9.44 GB)
telemt_user_octets_to_client{user="hello"} 111593040672 (103.93 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 121601.2 (33h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 404059
telemt_connections_bad_total 15106
telemt_handshake_timeouts_total 3856
telemt_upstream_connect_attempt_total 56996
telemt_upstream_connect_success_total 46764
telemt_upstream_connect_fail_total 10231
telemt_upstream_connect_attempts_per_request{bucket="1"} 56995
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28982
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17514
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 259
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10231
telemt_me_keepalive_timeout_total 4468
telemt_me_reconnect_attempts_total 112785
telemt_me_reconnect_success_total 24510
telemt_me_reader_eof_total 27963
telemt_me_idle_close_by_peer_total 27956
telemt_me_route_drop_no_conn_total 140107
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 339304
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1350
telemt_desync_full_logged_total 402
telemt_desync_suppressed_total 948
telemt_desync_frames_bucket_total{bucket="1_2"} 331
telemt_desync_frames_bucket_total{bucket="3_10"} 520
telemt_desync_frames_bucket_total{bucket="gt_10"} 499
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 27577
telemt_me_refill_failed_total 2753
telemt_me_writer_restored_same_endpoint_total 24500
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3067
telemt_user_connections_total{user="hello"} 355338
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 8319662492 (7.75 GB)
telemt_user_octets_to_client{user="hello"} 128517184361 (119.69 GB)
telemt_user_msgs_from_client{user="hello"} 425620
telemt_user_msgs_to_client{user="hello"} 774606
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 71772.6 (19h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116681
telemt_connections_bad_total 14928
telemt_handshake_timeouts_total 1387
telemt_upstream_connect_attempt_total 28554
telemt_upstream_connect_success_total 28294
telemt_upstream_connect_fail_total 260
telemt_upstream_connect_attempts_per_request{bucket="1"} 28554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13548
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 260
telemt_me_keepalive_timeout_total 1140
telemt_me_reconnect_attempts_total 33190
telemt_me_reconnect_success_total 19804
telemt_me_reader_eof_total 21245
telemt_me_idle_close_by_peer_total 21245
telemt_me_route_drop_no_conn_total 36285
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91701
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 400
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 321
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 218
telemt_desync_frames_bucket_total{bucket="gt_10"} 130
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 20402
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 19786
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 598
telemt_user_connections_total{user="hello"} 96599
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 1153492457 (1.07 GB)
telemt_user_octets_to_client{user="hello"} 30526921331 (28.43 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 121557.9 (33h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 741840
telemt_connections_bad_total 24647
telemt_handshake_timeouts_total 24395
telemt_upstream_connect_attempt_total 25382
telemt_upstream_connect_success_total 25251
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 25381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11845
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13376
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 2851
telemt_me_reconnect_attempts_total 23849
telemt_me_reconnect_success_total 19209
telemt_me_reader_eof_total 20611
telemt_me_idle_close_by_peer_total 20608
telemt_me_route_drop_no_conn_total 350526
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 695720
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 668
telemt_desync_full_logged_total 218
telemt_desync_suppressed_total 450
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 221
telemt_desync_frames_bucket_total{bucket="gt_10"} 211
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 19602
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 19202
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 393
telemt_user_connections_total{user="hello"} 668605
telemt_user_connections_current{user="hello"} 435
telemt_user_octets_from_client{user="hello"} 11631414552 (10.83 GB)
telemt_user_octets_to_client{user="hello"} 337119249252 (313.97 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 48
```