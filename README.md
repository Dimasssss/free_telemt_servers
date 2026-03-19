# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
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

# Server Metrics 2026-03-19 20:37:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 12024.0 (3h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 331184
telemt_connections_bad_total 15788
telemt_connections_current 1067
telemt_connections_me_current 1067
telemt_handshake_timeouts_total 4884
telemt_upstream_connect_attempt_total 1898
telemt_upstream_connect_success_total 1880
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 1898
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 966
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 1253
telemt_me_reconnect_success_total 1244
telemt_me_reader_eof_total 1310
telemt_me_idle_close_by_peer_total 1310
telemt_me_route_drop_no_conn_total 100776
telemt_me_route_drop_channel_closed_total 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 260499
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1292
telemt_desync_full_logged_total 435
telemt_desync_suppressed_total 857
telemt_desync_frames_bucket_total{bucket="1_2"} 271
telemt_desync_frames_bucket_total{bucket="3_10"} 375
telemt_desync_frames_bucket_total{bucket="gt_10"} 646
telemt_pool_swap_total 13
telemt_me_writer_close_signal_drop_total 30
telemt_me_writer_removed_unexpected_total 1275
telemt_me_writer_restored_same_endpoint_total 1231
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 260749
telemt_user_connections_current{user="hello"} 1067
telemt_user_octets_from_client{user="hello"} 10579312392 (9.85 GB)
telemt_user_octets_to_client{user="hello"} 94744965396 (88.24 GB)
telemt_user_unique_ips_current{user="hello"} 345
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 28479.3 (7h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2548460
telemt_connections_bad_total 109107
telemt_connections_current 2625
telemt_connections_me_current 2625
telemt_handshake_timeouts_total 48823
telemt_upstream_connect_attempt_total 5918
telemt_upstream_connect_success_total 5829
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 5918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2098
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 7386
telemt_me_reconnect_success_total 3158
telemt_me_reader_eof_total 3402
telemt_me_idle_close_by_peer_total 3402
telemt_me_route_drop_no_conn_total 1363293
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2165785
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9445
telemt_desync_full_logged_total 3085
telemt_desync_suppressed_total 6360
telemt_desync_frames_bucket_total{bucket="1_2"} 1746
telemt_desync_frames_bucket_total{bucket="3_10"} 3700
telemt_desync_frames_bucket_total{bucket="gt_10"} 3999
telemt_pool_swap_total 21
telemt_me_writer_close_signal_drop_total 38
telemt_me_writer_removed_unexpected_total 3320
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 3103
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 2165740
telemt_user_connections_current{user="hello"} 2625
telemt_user_octets_from_client{user="hello"} 33347526246 (31.06 GB)
telemt_user_octets_to_client{user="hello"} 764260757114 (711.77 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 988
telemt_user_unique_ips_recent_window{user="hello"} 283
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 28445.2 (7h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2183073
telemt_connections_bad_total 84326
telemt_connections_current 1991
telemt_connections_me_current 1991
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 27356
telemt_upstream_connect_attempt_total 31675
telemt_upstream_connect_success_total 30124
telemt_upstream_connect_fail_total 1551
telemt_upstream_connect_attempts_per_request{bucket="1"} 31675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24815
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4870
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 420
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1551
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 5923
telemt_me_reconnect_success_total 3381
telemt_me_reader_eof_total 3509
telemt_me_idle_close_by_peer_total 3508
telemt_me_route_drop_no_conn_total 1770524
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1866336
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7434
telemt_desync_full_logged_total 2324
telemt_desync_suppressed_total 5110
telemt_desync_frames_bucket_total{bucket="1_2"} 1855
telemt_desync_frames_bucket_total{bucket="3_10"} 2695
telemt_desync_frames_bucket_total{bucket="gt_10"} 2884
telemt_pool_swap_total 15
telemt_me_writer_close_signal_drop_total 291
telemt_me_writer_removed_unexpected_total 3845
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 3377
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 464
telemt_user_connections_total{user="hello"} 1890521
telemt_user_connections_current{user="hello"} 1991
telemt_user_octets_from_client{user="hello"} 31347013392 (29.19 GB)
telemt_user_octets_to_client{user="hello"} 455544197278 (424.26 GB)
telemt_user_msgs_from_client{user="hello"} 63004
telemt_user_msgs_to_client{user="hello"} 130023
telemt_user_unique_ips_current{user="hello"} 720
telemt_user_unique_ips_recent_window{user="hello"} 237
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 82168.3 (22h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5853554
telemt_connections_bad_total 1028855
telemt_connections_current 2578
telemt_connections_me_current 2578
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 107000
telemt_upstream_connect_attempt_total 66029
telemt_upstream_connect_success_total 63528
telemt_upstream_connect_fail_total 2501
telemt_upstream_connect_attempts_per_request{bucket="1"} 66029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53511
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8962
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1055
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2501
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 75644
telemt_me_reconnect_success_total 10228
telemt_me_reader_eof_total 10795
telemt_me_idle_close_by_peer_total 10792
telemt_me_route_drop_no_conn_total 2682046
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4123762
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18133
telemt_desync_full_logged_total 5623
telemt_desync_suppressed_total 12510
telemt_desync_frames_bucket_total{bucket="1_2"} 3097
telemt_desync_frames_bucket_total{bucket="3_10"} 7510
telemt_desync_frames_bucket_total{bucket="gt_10"} 7526
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 10484
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 10204
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 256
telemt_user_connections_total{user="hello"} 4171822
telemt_user_connections_current{user="hello"} 2578
telemt_user_octets_from_client{user="hello"} 65121536623 (60.65 GB)
telemt_user_octets_to_client{user="hello"} 1588581071508 (1.44 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 912
telemt_user_unique_ips_recent_window{user="hello"} 289
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 28408.4 (7h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 588253
telemt_connections_bad_total 45726
telemt_connections_current 538
telemt_connections_me_current 538
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 11356
telemt_upstream_connect_attempt_total 8330
telemt_upstream_connect_success_total 8133
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 8330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4675
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 552
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 3758
telemt_me_reconnect_success_total 3696
telemt_me_reader_eof_total 3832
telemt_me_idle_close_by_peer_total 3831
telemt_me_route_drop_no_conn_total 390010
telemt_me_route_drop_channel_closed_total 139
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 468239
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 881
telemt_me_writer_pick_total{mode="p2c",result="full"} 7065
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_writer_pick_blocking_fallback_total 8012
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1214
telemt_desync_full_logged_total 396
telemt_desync_suppressed_total 818
telemt_desync_frames_bucket_total{bucket="1_2"} 192
telemt_desync_frames_bucket_total{bucket="3_10"} 497
telemt_desync_frames_bucket_total{bucket="gt_10"} 525
telemt_pool_swap_total 21
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 138
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 3727
telemt_me_writer_restored_same_endpoint_total 3687
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 486878
telemt_user_connections_current{user="hello"} 538
telemt_user_octets_from_client{user="hello"} 5472475888 (5.10 GB)
telemt_user_octets_to_client{user="hello"} 105742590290 (98.48 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 28409.8 (7h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1718889
telemt_connections_bad_total 102474
telemt_connections_current 2191
telemt_connections_me_current 2191
telemt_handshake_timeouts_total 27850
telemt_upstream_connect_attempt_total 4720
telemt_upstream_connect_success_total 4685
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 4720
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2537
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2114
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 3262
telemt_me_reconnect_success_total 3231
telemt_me_reader_eof_total 3394
telemt_me_idle_close_by_peer_total 3394
telemt_me_route_drop_no_conn_total 649252
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1494632
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7909
telemt_desync_full_logged_total 2444
telemt_desync_suppressed_total 5465
telemt_desync_frames_bucket_total{bucket="1_2"} 1483
telemt_desync_frames_bucket_total{bucket="3_10"} 2749
telemt_desync_frames_bucket_total{bucket="gt_10"} 3677
telemt_pool_swap_total 26
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 3291
telemt_me_writer_restored_same_endpoint_total 3214
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 1493842
telemt_user_connections_current{user="hello"} 2191
telemt_user_octets_from_client{user="hello"} 25375200108 (23.63 GB)
telemt_user_octets_to_client{user="hello"} 722648297704 (673.02 GB)
telemt_user_unique_ips_current{user="hello"} 760
telemt_user_unique_ips_recent_window{user="hello"} 204
```