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

# Server Metrics 2026-03-19 13:38:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 191.4 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7929
telemt_connections_current 45
telemt_connections_me_current 45
telemt_handshake_timeouts_total 5871
telemt_upstream_connect_attempt_total 232
telemt_upstream_connect_success_total 231
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 103
telemt_me_reconnect_success_total 100
telemt_me_reader_eof_total 40
telemt_me_idle_close_by_peer_total 40
telemt_me_route_drop_no_conn_total 122
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 494
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_desync_total 8
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_me_writer_close_signal_drop_total 12
telemt_me_writer_removed_unexpected_total 52
telemt_me_writer_restored_same_endpoint_total 84
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 10
telemt_me_async_recovery_trigger_total 100
telemt_user_connections_total{user="hello"} 566
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 25873891 (24.68 MB)
telemt_user_octets_to_client{user="hello"} 128797088 (122.83 MB)
telemt_user_msgs_from_client{user="hello"} 261
telemt_user_msgs_to_client{user="hello"} 430
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 3327.6 (0h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 375384
telemt_connections_bad_total 10030
telemt_connections_current 3518
telemt_connections_me_current 3518
telemt_handshake_timeouts_total 4784
telemt_upstream_connect_attempt_total 2077
telemt_upstream_connect_success_total 2065
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 2342
telemt_me_reconnect_success_total 639
telemt_me_reader_eof_total 648
telemt_me_idle_close_by_peer_total 648
telemt_me_route_drop_no_conn_total 336975
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 336473
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1003
telemt_desync_full_logged_total 333
telemt_desync_suppressed_total 670
telemt_desync_frames_bucket_total{bucket="1_2"} 162
telemt_desync_frames_bucket_total{bucket="3_10"} 383
telemt_desync_frames_bucket_total{bucket="gt_10"} 458
telemt_me_writer_close_signal_drop_total 25
telemt_me_writer_removed_unexpected_total 673
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 584
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 337340
telemt_user_connections_current{user="hello"} 3518
telemt_user_octets_from_client{user="hello"} 5139321150 (4.79 GB)
telemt_user_octets_to_client{user="hello"} 82877591922 (77.19 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1271
telemt_user_unique_ips_recent_window{user="hello"} 530
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 3308.2 (0h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 444555
telemt_connections_bad_total 37214
telemt_connections_current 2981
telemt_connections_me_current 2981
telemt_handshake_timeouts_total 4658
telemt_upstream_connect_attempt_total 512
telemt_upstream_connect_success_total 508
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 512
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 200
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 1205
telemt_me_reconnect_success_total 307
telemt_me_reader_eof_total 237
telemt_me_idle_close_by_peer_total 236
telemt_me_route_drop_no_conn_total 482652
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 328660
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1034
telemt_desync_full_logged_total 249
telemt_desync_suppressed_total 785
telemt_desync_frames_bucket_total{bucket="1_2"} 303
telemt_desync_frames_bucket_total{bucket="3_10"} 374
telemt_desync_frames_bucket_total{bucket="gt_10"} 357
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 27
telemt_me_writer_removed_unexpected_total 257
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 306
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 326503
telemt_user_connections_current{user="hello"} 2981
telemt_user_octets_from_client{user="hello"} 2353695132 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 71332724604 (66.43 GB)
telemt_user_unique_ips_current{user="hello"} 1030
telemt_user_unique_ips_recent_window{user="hello"} 473
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 3293.4 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 313148
telemt_connections_bad_total 36467
telemt_connections_current 2921
telemt_connections_me_current 2921
telemt_handshake_timeouts_total 4358
telemt_upstream_connect_attempt_total 4037
telemt_upstream_connect_success_total 3888
telemt_upstream_connect_fail_total 149
telemt_upstream_connect_attempts_per_request{bucket="1"} 4037
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3477
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 369
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 149
telemt_me_reconnect_attempts_total 377
telemt_me_reconnect_success_total 363
telemt_me_reader_eof_total 337
telemt_me_idle_close_by_peer_total 336
telemt_me_route_drop_no_conn_total 186820
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 246002
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 862
telemt_desync_full_logged_total 286
telemt_desync_suppressed_total 576
telemt_desync_frames_bucket_total{bucket="1_2"} 159
telemt_desync_frames_bucket_total{bucket="3_10"} 307
telemt_desync_frames_bucket_total{bucket="gt_10"} 396
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 24
telemt_me_writer_removed_unexpected_total 351
telemt_me_writer_restored_same_endpoint_total 360
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 402
telemt_user_connections_total{user="hello"} 249134
telemt_user_connections_current{user="hello"} 2921
telemt_user_octets_from_client{user="hello"} 2886124047 (2.69 GB)
telemt_user_octets_to_client{user="hello"} 54878726394 (51.11 GB)
telemt_user_msgs_from_client{user="hello"} 5613
telemt_user_msgs_to_client{user="hello"} 6373
telemt_user_unique_ips_current{user="hello"} 940
telemt_user_unique_ips_recent_window{user="hello"} 488
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 57016.7 (15h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3858255
telemt_connections_bad_total 750121
telemt_connections_current 3602
telemt_connections_me_current 3602
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 77130
telemt_upstream_connect_attempt_total 61938
telemt_upstream_connect_success_total 59455
telemt_upstream_connect_fail_total 2483
telemt_upstream_connect_attempts_per_request{bucket="1"} 61938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7026
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1014
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2483
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 70466
telemt_me_reconnect_success_total 7410
telemt_me_reader_eof_total 7745
telemt_me_idle_close_by_peer_total 7742
telemt_me_route_drop_no_conn_total 1712036
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2609021
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11389
telemt_desync_full_logged_total 3505
telemt_desync_suppressed_total 7884
telemt_desync_frames_bucket_total{bucket="1_2"} 1999
telemt_desync_frames_bucket_total{bucket="3_10"} 4877
telemt_desync_frames_bucket_total{bucket="gt_10"} 4513
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 7539
telemt_me_refill_failed_total 1967
telemt_me_writer_restored_same_endpoint_total 7386
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 2657753
telemt_user_connections_current{user="hello"} 3602
telemt_user_octets_from_client{user="hello"} 42742659227 (39.81 GB)
telemt_user_octets_to_client{user="hello"} 966658843200 (900.27 GB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1141
telemt_user_unique_ips_recent_window{user="hello"} 548
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 3258.2 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82682
telemt_connections_bad_total 3726
telemt_connections_current 974
telemt_connections_me_current 974
telemt_handshake_timeouts_total 4593
telemt_upstream_connect_attempt_total 550
telemt_upstream_connect_success_total 548
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 550
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 294
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 250
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 352
telemt_me_reconnect_success_total 342
telemt_me_reader_eof_total 292
telemt_me_idle_close_by_peer_total 292
telemt_me_route_drop_no_conn_total 71049
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71352
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 464
telemt_me_writer_pick_total{mode="p2c",result="full"} 2833
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_writer_pick_blocking_fallback_total 3285
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 144
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 88
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 29
telemt_me_writer_removed_unexpected_total 307
telemt_me_writer_restored_same_endpoint_total 333
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 152
telemt_me_async_recovery_trigger_total 996
telemt_user_connections_total{user="hello"} 71444
telemt_user_connections_current{user="hello"} 974
telemt_user_octets_from_client{user="hello"} 1013249384 (966.31 MB)
telemt_user_octets_to_client{user="hello"} 16064836772 (14.96 GB)
telemt_user_unique_ips_current{user="hello"} 354
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 3258.0 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 233420
telemt_connections_bad_total 22194
telemt_connections_current 3363
telemt_connections_me_current 3363
telemt_handshake_timeouts_total 3868
telemt_upstream_connect_attempt_total 504
telemt_upstream_connect_success_total 501
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 305
telemt_me_reconnect_success_total 300
telemt_me_reader_eof_total 296
telemt_me_idle_close_by_peer_total 296
telemt_me_route_drop_no_conn_total 68081
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 199922
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 933
telemt_desync_full_logged_total 269
telemt_desync_suppressed_total 664
telemt_desync_frames_bucket_total{bucket="1_2"} 150
telemt_desync_frames_bucket_total{bucket="3_10"} 334
telemt_desync_frames_bucket_total{bucket="gt_10"} 449
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 307
telemt_me_writer_restored_same_endpoint_total 283
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 199881
telemt_user_connections_current{user="hello"} 3363
telemt_user_octets_from_client{user="hello"} 2439606836 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 84542594116 (78.74 GB)
telemt_user_unique_ips_current{user="hello"} 1100
telemt_user_unique_ips_recent_window{user="hello"} 482
```