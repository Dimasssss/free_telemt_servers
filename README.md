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

# Server Metrics 2026-03-19 13:49:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 805.8 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49835
telemt_connections_bad_total 7
telemt_connections_current 95
telemt_connections_me_current 95
telemt_handshake_timeouts_total 43849
telemt_upstream_connect_attempt_total 462
telemt_upstream_connect_success_total 461
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 462
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 238
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 333
telemt_me_reconnect_success_total 327
telemt_me_reader_eof_total 259
telemt_me_idle_close_by_peer_total 259
telemt_me_route_drop_no_conn_total 870
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2097
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_desync_total 32
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_me_writer_close_signal_drop_total 16
telemt_me_writer_removed_unexpected_total 275
telemt_me_writer_restored_same_endpoint_total 311
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 10
telemt_me_async_recovery_trigger_total 102
telemt_user_connections_total{user="hello"} 2057
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 32102755 (30.62 MB)
telemt_user_octets_to_client{user="hello"} 579084652 (552.26 MB)
telemt_user_msgs_from_client{user="hello"} 261
telemt_user_msgs_to_client{user="hello"} 430
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 3942.0 (1h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 429148
telemt_connections_bad_total 11747
telemt_connections_current 3203
telemt_connections_me_current 3203
telemt_handshake_timeouts_total 6384
telemt_upstream_connect_attempt_total 2179
telemt_upstream_connect_success_total 2167
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1723
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 439
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 3552
telemt_me_reconnect_success_total 697
telemt_me_reader_eof_total 740
telemt_me_idle_close_by_peer_total 740
telemt_me_route_drop_no_conn_total 385744
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 384729
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1150
telemt_desync_full_logged_total 381
telemt_desync_suppressed_total 769
telemt_desync_frames_bucket_total{bucket="1_2"} 195
telemt_desync_frames_bucket_total{bucket="3_10"} 442
telemt_desync_frames_bucket_total{bucket="gt_10"} 513
telemt_me_writer_close_signal_drop_total 25
telemt_me_writer_removed_unexpected_total 768
telemt_me_refill_failed_total 89
telemt_me_writer_restored_same_endpoint_total 642
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 385584
telemt_user_connections_current{user="hello"} 3203
telemt_user_octets_from_client{user="hello"} 5533289458 (5.15 GB)
telemt_user_octets_to_client{user="hello"} 94699359854 (88.20 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1231
telemt_user_unique_ips_recent_window{user="hello"} 547
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 3920.2 (1h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 491522
telemt_connections_bad_total 42709
telemt_connections_current 2961
telemt_connections_me_current 2961
telemt_handshake_timeouts_total 5001
telemt_upstream_connect_attempt_total 642
telemt_upstream_connect_success_total 636
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 642
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 388
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 248
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 1286
telemt_me_reconnect_success_total 388
telemt_me_reader_eof_total 320
telemt_me_idle_close_by_peer_total 319
telemt_me_route_drop_no_conn_total 497673
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 367255
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1215
telemt_desync_full_logged_total 300
telemt_desync_suppressed_total 915
telemt_desync_frames_bucket_total{bucket="1_2"} 338
telemt_desync_frames_bucket_total{bucket="3_10"} 454
telemt_desync_frames_bucket_total{bucket="gt_10"} 423
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 27
telemt_me_writer_removed_unexpected_total 341
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 387
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 365088
telemt_user_connections_current{user="hello"} 2961
telemt_user_octets_from_client{user="hello"} 2879271212 (2.68 GB)
telemt_user_octets_to_client{user="hello"} 84448744460 (78.65 GB)
telemt_user_unique_ips_current{user="hello"} 1071
telemt_user_unique_ips_recent_window{user="hello"} 422
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 3908.3 (1h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 353777
telemt_connections_bad_total 37536
telemt_connections_current 2900
telemt_connections_me_current 2900
telemt_handshake_timeouts_total 5773
telemt_upstream_connect_attempt_total 4163
telemt_upstream_connect_success_total 4006
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 4163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 422
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 455
telemt_me_reconnect_success_total 433
telemt_me_reader_eof_total 407
telemt_me_idle_close_by_peer_total 406
telemt_me_route_drop_no_conn_total 210240
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 280616
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1055
telemt_desync_full_logged_total 353
telemt_desync_suppressed_total 702
telemt_desync_frames_bucket_total{bucket="1_2"} 192
telemt_desync_frames_bucket_total{bucket="3_10"} 379
telemt_desync_frames_bucket_total{bucket="gt_10"} 484
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 24
telemt_me_writer_removed_unexpected_total 426
telemt_me_writer_restored_same_endpoint_total 430
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 402
telemt_user_connections_total{user="hello"} 283742
telemt_user_connections_current{user="hello"} 2900
telemt_user_octets_from_client{user="hello"} 3311082667 (3.08 GB)
telemt_user_octets_to_client{user="hello"} 65041783786 (60.57 GB)
telemt_user_msgs_from_client{user="hello"} 5613
telemt_user_msgs_to_client{user="hello"} 6373
telemt_user_unique_ips_current{user="hello"} 988
telemt_user_unique_ips_recent_window{user="hello"} 439
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 57631.2 (16h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3927057
telemt_connections_bad_total 759374
telemt_connections_current 3739
telemt_connections_me_current 3739
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 77993
telemt_upstream_connect_attempt_total 62010
telemt_upstream_connect_success_total 59527
telemt_upstream_connect_fail_total 2483
telemt_upstream_connect_attempts_per_request{bucket="1"} 62010
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51443
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7070
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1014
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2483
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 70532
telemt_me_reconnect_success_total 7475
telemt_me_reader_eof_total 7812
telemt_me_idle_close_by_peer_total 7809
telemt_me_route_drop_no_conn_total 1788344
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2663411
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
telemt_desync_total 11532
telemt_desync_full_logged_total 3560
telemt_desync_suppressed_total 7972
telemt_desync_frames_bucket_total{bucket="1_2"} 2026
telemt_desync_frames_bucket_total{bucket="3_10"} 4940
telemt_desync_frames_bucket_total{bucket="gt_10"} 4566
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 7606
telemt_me_refill_failed_total 1967
telemt_me_writer_restored_same_endpoint_total 7451
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 2712139
telemt_user_connections_current{user="hello"} 3739
telemt_user_octets_from_client{user="hello"} 44195019319 (41.16 GB)
telemt_user_octets_to_client{user="hello"} 977406259632 (910.28 GB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1202
telemt_user_unique_ips_recent_window{user="hello"} 830
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 3872.3 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101019
telemt_connections_bad_total 4984
telemt_connections_current 931
telemt_connections_me_current 931
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 4704
telemt_upstream_connect_attempt_total 3333
telemt_upstream_connect_success_total 3197
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 3333
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1942
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_reconnect_attempts_total 436
telemt_me_reconnect_success_total 419
telemt_me_reader_eof_total 369
telemt_me_idle_close_by_peer_total 369
telemt_me_route_drop_no_conn_total 81337
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 84682
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
telemt_desync_total 172
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 105
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 76
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 30
telemt_me_writer_removed_unexpected_total 380
telemt_me_writer_restored_same_endpoint_total 410
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 179
telemt_me_async_recovery_trigger_total 1239
telemt_user_connections_total{user="hello"} 87324
telemt_user_connections_current{user="hello"} 931
telemt_user_octets_from_client{user="hello"} 1218772284 (1.14 GB)
telemt_user_octets_to_client{user="hello"} 19831393066 (18.47 GB)
telemt_user_msgs_from_client{user="hello"} 7378
telemt_user_msgs_to_client{user="hello"} 12667
telemt_user_unique_ips_current{user="hello"} 340
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 3872.7 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 272333
telemt_connections_bad_total 23435
telemt_connections_current 3085
telemt_connections_me_current 3085
telemt_handshake_timeouts_total 4819
telemt_upstream_connect_attempt_total 615
telemt_upstream_connect_success_total 611
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 615
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 284
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 371
telemt_me_reconnect_success_total 365
telemt_me_reader_eof_total 370
telemt_me_idle_close_by_peer_total 370
telemt_me_route_drop_no_conn_total 80139
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 235316
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1052
telemt_desync_full_logged_total 316
telemt_desync_suppressed_total 736
telemt_desync_frames_bucket_total{bucket="1_2"} 172
telemt_desync_frames_bucket_total{bucket="3_10"} 375
telemt_desync_frames_bucket_total{bucket="gt_10"} 505
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 375
telemt_me_writer_restored_same_endpoint_total 348
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 235244
telemt_user_connections_current{user="hello"} 3085
telemt_user_octets_from_client{user="hello"} 2836579852 (2.64 GB)
telemt_user_octets_to_client{user="hello"} 99040200696 (92.24 GB)
telemt_user_unique_ips_current{user="hello"} 1051
telemt_user_unique_ips_recent_window{user="hello"} 419
```