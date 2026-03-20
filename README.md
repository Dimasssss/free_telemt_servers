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

# Server Metrics 2026-03-20 01:18:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 28875.2 (8h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 547535
telemt_connections_bad_total 35534
telemt_connections_current 757
telemt_connections_me_current 757
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 7959
telemt_upstream_connect_attempt_total 6161
telemt_upstream_connect_success_total 6080
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 6161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2534
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 3537
telemt_me_reconnect_success_total 3502
telemt_me_reader_eof_total 3687
telemt_me_idle_close_by_peer_total 3686
telemt_me_route_drop_no_conn_total 159653
telemt_me_route_drop_channel_closed_total 56
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 436987
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2084
telemt_desync_full_logged_total 750
telemt_desync_suppressed_total 1334
telemt_desync_frames_bucket_total{bucket="1_2"} 425
telemt_desync_frames_bucket_total{bucket="3_10"} 712
telemt_desync_frames_bucket_total{bucket="gt_10"} 947
telemt_pool_swap_total 31
telemt_me_writer_close_signal_drop_total 39
telemt_me_writer_removed_unexpected_total 3525
telemt_me_writer_restored_same_endpoint_total 3489
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 438417
telemt_user_connections_current{user="hello"} 757
telemt_user_octets_from_client{user="hello"} 29632898984 (27.60 GB)
telemt_user_octets_to_client{user="hello"} 157446883873 (146.63 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 45329.7 (12h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2980532
telemt_connections_bad_total 125796
telemt_connections_current 1425
telemt_connections_me_current 1425
telemt_handshake_timeouts_total 65080
telemt_upstream_connect_attempt_total 9068
telemt_upstream_connect_success_total 8915
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 9068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3657
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 9655
telemt_me_reconnect_success_total 5414
telemt_me_reader_eof_total 5796
telemt_me_idle_close_by_peer_total 5796
telemt_me_route_drop_no_conn_total 1497375
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2552945
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11051
telemt_desync_full_logged_total 3634
telemt_desync_suppressed_total 7417
telemt_desync_frames_bucket_total{bucket="1_2"} 2117
telemt_desync_frames_bucket_total{bucket="3_10"} 4325
telemt_desync_frames_bucket_total{bucket="gt_10"} 4609
telemt_pool_swap_total 38
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 51
telemt_me_writer_removed_unexpected_total 5606
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 5359
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 192
telemt_user_connections_total{user="hello"} 2552727
telemt_user_connections_current{user="hello"} 1425
telemt_user_octets_from_client{user="hello"} 39160432222 (36.47 GB)
telemt_user_octets_to_client{user="hello"} 931650043794 (867.67 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 643
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 45307.8 (12h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2926124
telemt_connections_bad_total 472372
telemt_connections_current 1033
telemt_connections_me_current 1033
telemt_handshake_timeouts_total 42445
telemt_upstream_connect_attempt_total 7306
telemt_upstream_connect_success_total 7252
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 7306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3698
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3537
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5909
telemt_me_reconnect_success_total 4976
telemt_me_reader_eof_total 5218
telemt_me_idle_close_by_peer_total 5217
telemt_me_route_drop_no_conn_total 1914800
telemt_me_route_drop_channel_closed_total 172
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2020605
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7621
telemt_desync_full_logged_total 2309
telemt_desync_suppressed_total 5312
telemt_desync_frames_bucket_total{bucket="1_2"} 1878
telemt_desync_frames_bucket_total{bucket="3_10"} 2903
telemt_desync_frames_bucket_total{bucket="gt_10"} 2840
telemt_pool_swap_total 44
telemt_me_writer_close_signal_drop_total 69
telemt_me_writer_removed_unexpected_total 5024
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4975
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 2016252
telemt_user_connections_current{user="hello"} 1033
telemt_user_octets_from_client{user="hello"} 29833846556 (27.78 GB)
telemt_user_octets_to_client{user="hello"} 769259346296 (716.43 GB)
telemt_user_unique_ips_current{user="hello"} 452
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 45295.8 (12h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2540717
telemt_connections_bad_total 120283
telemt_connections_current 955
telemt_connections_me_current 955
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 31030
telemt_upstream_connect_attempt_total 55259
telemt_upstream_connect_success_total 50988
telemt_upstream_connect_fail_total 4271
telemt_upstream_connect_attempts_per_request{bucket="1"} 55259
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43038
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7397
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 528
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4271
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 8302
telemt_me_reconnect_success_total 5467
telemt_me_reader_eof_total 5678
telemt_me_idle_close_by_peer_total 5677
telemt_me_route_drop_no_conn_total 1860484
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2124388
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8285
telemt_desync_full_logged_total 2618
telemt_desync_suppressed_total 5667
telemt_desync_frames_bucket_total{bucket="1_2"} 2038
telemt_desync_frames_bucket_total{bucket="3_10"} 3014
telemt_desync_frames_bucket_total{bucket="gt_10"} 3233
telemt_pool_swap_total 31
telemt_me_writer_close_signal_drop_total 476
telemt_me_writer_removed_unexpected_total 6089
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 5463
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 622
telemt_user_connections_total{user="hello"} 2166459
telemt_user_connections_current{user="hello"} 955
telemt_user_octets_from_client{user="hello"} 35409770185 (32.98 GB)
telemt_user_octets_to_client{user="hello"} 606762103369 (565.09 GB)
telemt_user_msgs_from_client{user="hello"} 240837
telemt_user_msgs_to_client{user="hello"} 1741640
telemt_user_unique_ips_current{user="hello"} 387
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 99019.0 (27h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6251024
telemt_connections_bad_total 1041356
telemt_connections_current 1238
telemt_connections_me_current 1238
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 113066
telemt_upstream_connect_attempt_total 127203
telemt_upstream_connect_success_total 93920
telemt_upstream_connect_fail_total 33283
telemt_upstream_connect_attempts_per_request{bucket="1"} 127203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12341
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1433
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33283
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 78351
telemt_me_reconnect_success_total 12681
telemt_me_reader_eof_total 13660
telemt_me_idle_close_by_peer_total 13646
telemt_me_route_drop_no_conn_total 2791965
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4427670
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
telemt_desync_total 19474
telemt_desync_full_logged_total 6163
telemt_desync_suppressed_total 13311
telemt_desync_frames_bucket_total{bucket="1_2"} 3422
telemt_desync_frames_bucket_total{bucket="3_10"} 8012
telemt_desync_frames_bucket_total{bucket="gt_10"} 8040
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 12987
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 12656
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 306
telemt_user_connections_total{user="hello"} 4502884
telemt_user_connections_current{user="hello"} 1238
telemt_user_octets_from_client{user="hello"} 70730651664 (65.87 GB)
telemt_user_octets_to_client{user="hello"} 1735199512960 (1.58 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 518
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 45259.0 (12h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 704650
telemt_connections_bad_total 74628
telemt_connections_current 317
telemt_connections_me_current 317
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12992
telemt_upstream_connect_attempt_total 13423
telemt_upstream_connect_success_total 13092
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13422
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6818
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 6475
telemt_me_reconnect_success_total 6367
telemt_me_reader_eof_total 6681
telemt_me_idle_close_by_peer_total 6678
telemt_me_route_drop_no_conn_total 467296
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 578915
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
telemt_desync_total 1397
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 874
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 576
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 40
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 150
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 6427
telemt_me_writer_restored_same_endpoint_total 6358
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 567061
telemt_user_connections_current{user="hello"} 317
telemt_user_octets_from_client{user="hello"} 7300726991 (6.80 GB)
telemt_user_octets_to_client{user="hello"} 143108325522 (133.28 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 45260.3 (12h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2005815
telemt_connections_bad_total 119959
telemt_connections_current 1172
telemt_connections_me_current 1172
telemt_handshake_timeouts_total 37256
telemt_upstream_connect_attempt_total 8060
telemt_upstream_connect_success_total 8001
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 8060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3652
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 5760
telemt_me_reconnect_success_total 5719
telemt_me_reader_eof_total 6037
telemt_me_idle_close_by_peer_total 6037
telemt_me_route_drop_no_conn_total 739335
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1728882
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9139
telemt_desync_full_logged_total 2938
telemt_desync_suppressed_total 6201
telemt_desync_frames_bucket_total{bucket="1_2"} 1702
telemt_desync_frames_bucket_total{bucket="3_10"} 3210
telemt_desync_frames_bucket_total{bucket="gt_10"} 4227
telemt_pool_swap_total 45
telemt_me_writer_close_signal_drop_total 39
telemt_me_writer_removed_unexpected_total 5806
telemt_me_writer_restored_same_endpoint_total 5702
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 1727991
telemt_user_connections_current{user="hello"} 1172
telemt_user_octets_from_client{user="hello"} 29560402068 (27.53 GB)
telemt_user_octets_to_client{user="hello"} 875117817744 (815.02 GB)
telemt_user_unique_ips_current{user="hello"} 464
telemt_user_unique_ips_recent_window{user="hello"} 93
```