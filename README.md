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

# Server Metrics 2026-03-19 14:14:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 654.4 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59147
telemt_connections_bad_total 2
telemt_connections_current 111
telemt_connections_direct_current 111
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_demotions_total 156
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 49153
telemt_upstream_connect_attempt_total 2187
telemt_upstream_connect_success_total 2187
telemt_upstream_connect_attempts_per_request{bucket="1"} 2187
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 185
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2185
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 19215257 (18.33 MB)
telemt_user_octets_to_client{user="hello"} 622225720 (593.40 MB)
telemt_user_msgs_from_client{user="hello"} 22289
telemt_user_msgs_to_client{user="hello"} 53224
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 5474.2 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 590873
telemt_connections_bad_total 18595
telemt_connections_current 3693
telemt_connections_me_current 3693
telemt_handshake_timeouts_total 10326
telemt_upstream_connect_attempt_total 2377
telemt_upstream_connect_success_total 2363
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 5022
telemt_me_reconnect_success_total 822
telemt_me_reader_eof_total 905
telemt_me_idle_close_by_peer_total 905
telemt_me_route_drop_no_conn_total 527670
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 522376
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1780
telemt_desync_full_logged_total 565
telemt_desync_suppressed_total 1215
telemt_desync_frames_bucket_total{bucket="1_2"} 329
telemt_desync_frames_bucket_total{bucket="3_10"} 674
telemt_desync_frames_bucket_total{bucket="gt_10"} 777
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 935
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 767
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 523201
telemt_user_connections_current{user="hello"} 3693
telemt_user_octets_from_client{user="hello"} 6953917390 (6.48 GB)
telemt_user_octets_to_client{user="hello"} 130678867118 (121.70 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1316
telemt_user_unique_ips_recent_window{user="hello"} 625
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 5440.1 (1h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 484513
telemt_connections_bad_total 39387
telemt_connections_current 3215
telemt_connections_me_current 3215
telemt_handshake_timeouts_total 7572
telemt_upstream_connect_attempt_total 9836
telemt_upstream_connect_success_total 9360
telemt_upstream_connect_fail_total 476
telemt_upstream_connect_attempts_per_request{bucket="1"} 9836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7723
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1474
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 476
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 791
telemt_me_reconnect_success_total 603
telemt_me_reader_eof_total 570
telemt_me_idle_close_by_peer_total 569
telemt_me_route_drop_no_conn_total 321125
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 391116
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1713
telemt_desync_full_logged_total 556
telemt_desync_suppressed_total 1157
telemt_desync_frames_bucket_total{bucket="1_2"} 343
telemt_desync_frames_bucket_total{bucket="3_10"} 651
telemt_desync_frames_bucket_total{bucket="gt_10"} 719
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 76
telemt_me_writer_removed_unexpected_total 704
telemt_me_writer_restored_same_endpoint_total 599
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 399156
telemt_user_connections_current{user="hello"} 3215
telemt_user_octets_from_client{user="hello"} 6811327227 (6.34 GB)
telemt_user_octets_to_client{user="hello"} 87257128552 (81.26 GB)
telemt_user_msgs_from_client{user="hello"} 16739
telemt_user_msgs_to_client{user="hello"} 18599
telemt_user_unique_ips_current{user="hello"} 976
telemt_user_unique_ips_recent_window{user="hello"} 507
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 59163.5 (16h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4079754
telemt_connections_bad_total 772441
telemt_connections_current 3757
telemt_connections_me_current 3757
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 79582
telemt_upstream_connect_attempt_total 62395
telemt_upstream_connect_success_total 59911
telemt_upstream_connect_fail_total 2484
telemt_upstream_connect_attempts_per_request{bucket="1"} 62395
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51639
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7255
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1017
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2484
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 71787
telemt_me_reconnect_success_total 7767
telemt_me_reader_eof_total 8137
telemt_me_idle_close_by_peer_total 8134
telemt_me_route_drop_no_conn_total 1948241
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2791723
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
telemt_desync_total 12073
telemt_desync_full_logged_total 3714
telemt_desync_suppressed_total 8359
telemt_desync_frames_bucket_total{bucket="1_2"} 2084
telemt_desync_frames_bucket_total{bucket="3_10"} 5176
telemt_desync_frames_bucket_total{bucket="gt_10"} 4813
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 7932
telemt_me_refill_failed_total 1997
telemt_me_writer_restored_same_endpoint_total 7743
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 2840407
telemt_user_connections_current{user="hello"} 3757
telemt_user_octets_from_client{user="hello"} 45496193079 (42.37 GB)
telemt_user_octets_to_client{user="hello"} 1013389455780 (943.79 GB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1193
telemt_user_unique_ips_recent_window{user="hello"} 592
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 5405.9 (1h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131059
telemt_connections_bad_total 6284
telemt_connections_current 931
telemt_connections_me_current 931
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 4882
telemt_upstream_connect_attempt_total 3554
telemt_upstream_connect_success_total 3417
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 3554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2069
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_reconnect_attempts_total 613
telemt_me_reconnect_success_total 590
telemt_me_reader_eof_total 551
telemt_me_idle_close_by_peer_total 551
telemt_me_route_drop_no_conn_total 95717
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111397
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
telemt_desync_total 252
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 168
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 105
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 552
telemt_me_writer_restored_same_endpoint_total 581
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 179
telemt_me_async_recovery_trigger_total 1239
telemt_user_connections_total{user="hello"} 114030
telemt_user_connections_current{user="hello"} 931
telemt_user_octets_from_client{user="hello"} 1529651024 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 26794573858 (24.95 GB)
telemt_user_msgs_from_client{user="hello"} 7378
telemt_user_msgs_to_client{user="hello"} 12667
telemt_user_unique_ips_current{user="hello"} 354
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 5404.9 (1h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 373808
telemt_connections_bad_total 28264
telemt_connections_current 3141
telemt_connections_me_current 3141
telemt_handshake_timeouts_total 6795
telemt_upstream_connect_attempt_total 870
telemt_upstream_connect_success_total 865
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 474
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 391
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 578
telemt_me_reconnect_success_total 566
telemt_me_reader_eof_total 568
telemt_me_idle_close_by_peer_total 568
telemt_me_route_drop_no_conn_total 128193
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 326644
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1657
telemt_desync_full_logged_total 496
telemt_desync_suppressed_total 1161
telemt_desync_frames_bucket_total{bucket="1_2"} 277
telemt_desync_frames_bucket_total{bucket="3_10"} 550
telemt_desync_frames_bucket_total{bucket="gt_10"} 830
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 24
telemt_me_writer_removed_unexpected_total 584
telemt_me_writer_restored_same_endpoint_total 549
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 326396
telemt_user_connections_current{user="hello"} 3141
telemt_user_octets_from_client{user="hello"} 3814764748 (3.55 GB)
telemt_user_octets_to_client{user="hello"} 134897630624 (125.63 GB)
telemt_user_unique_ips_current{user="hello"} 1034
telemt_user_unique_ips_recent_window{user="hello"} 470
```