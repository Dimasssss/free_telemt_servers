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

# Server Metrics 2026-03-20 01:29:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 29488.2 (8h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 556572
telemt_connections_bad_total 36073
telemt_connections_current 769
telemt_connections_me_current 769
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 8471
telemt_upstream_connect_attempt_total 6262
telemt_upstream_connect_success_total 6181
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 6262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3568
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2585
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 3626
telemt_me_reconnect_success_total 3590
telemt_me_reader_eof_total 3784
telemt_me_idle_close_by_peer_total 3783
telemt_me_route_drop_no_conn_total 161655
telemt_me_route_drop_channel_closed_total 56
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 444314
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2108
telemt_desync_full_logged_total 756
telemt_desync_suppressed_total 1352
telemt_desync_frames_bucket_total{bucket="1_2"} 427
telemt_desync_frames_bucket_total{bucket="3_10"} 722
telemt_desync_frames_bucket_total{bucket="gt_10"} 959
telemt_pool_swap_total 32
telemt_me_writer_close_signal_drop_total 39
telemt_me_writer_removed_unexpected_total 3614
telemt_me_writer_restored_same_endpoint_total 3577
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 445743
telemt_user_connections_current{user="hello"} 769
telemt_user_octets_from_client{user="hello"} 29709935036 (27.67 GB)
telemt_user_octets_to_client{user="hello"} 159106781073 (148.18 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 311
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 45943.0 (12h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2990770
telemt_connections_bad_total 125825
telemt_connections_current 1375
telemt_connections_me_current 1375
telemt_handshake_timeouts_total 65829
telemt_upstream_connect_attempt_total 9135
telemt_upstream_connect_success_total 8982
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 9135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3700
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 9711
telemt_me_reconnect_success_total 5469
telemt_me_reader_eof_total 5853
telemt_me_idle_close_by_peer_total 5853
telemt_me_route_drop_no_conn_total 1500623
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2562291
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11096
telemt_desync_full_logged_total 3649
telemt_desync_suppressed_total 7447
telemt_desync_frames_bucket_total{bucket="1_2"} 2125
telemt_desync_frames_bucket_total{bucket="3_10"} 4342
telemt_desync_frames_bucket_total{bucket="gt_10"} 4629
telemt_pool_swap_total 38
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 51
telemt_me_writer_removed_unexpected_total 5663
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 5414
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 2562072
telemt_user_connections_current{user="hello"} 1375
telemt_user_octets_from_client{user="hello"} 39240732818 (36.55 GB)
telemt_user_octets_to_client{user="hello"} 935830525074 (871.56 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 623
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 45921.1 (12h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2938317
telemt_connections_bad_total 473298
telemt_connections_current 1067
telemt_connections_me_current 1067
telemt_handshake_timeouts_total 42819
telemt_upstream_connect_attempt_total 7357
telemt_upstream_connect_success_total 7303
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 7357
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3721
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3565
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5959
telemt_me_reconnect_success_total 5026
telemt_me_reader_eof_total 5270
telemt_me_idle_close_by_peer_total 5269
telemt_me_route_drop_no_conn_total 1917734
telemt_me_route_drop_channel_closed_total 173
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2027709
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7632
telemt_desync_full_logged_total 2316
telemt_desync_suppressed_total 5316
telemt_desync_frames_bucket_total{bucket="1_2"} 1880
telemt_desync_frames_bucket_total{bucket="3_10"} 2910
telemt_desync_frames_bucket_total{bucket="gt_10"} 2842
telemt_pool_swap_total 44
telemt_me_writer_close_signal_drop_total 69
telemt_me_writer_removed_unexpected_total 5076
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5025
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 2023339
telemt_user_connections_current{user="hello"} 1067
telemt_user_octets_from_client{user="hello"} 29904351344 (27.85 GB)
telemt_user_octets_to_client{user="hello"} 772073146240 (719.05 GB)
telemt_user_unique_ips_current{user="hello"} 452
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 45909.0 (12h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2552281
telemt_connections_bad_total 123822
telemt_connections_current 976
telemt_connections_me_current 976
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 31081
telemt_upstream_connect_attempt_total 55311
telemt_upstream_connect_success_total 51038
telemt_upstream_connect_fail_total 4273
telemt_upstream_connect_attempts_per_request{bucket="1"} 55311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7430
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 528
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4273
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 8354
telemt_me_reconnect_success_total 5517
telemt_me_reader_eof_total 5729
telemt_me_idle_close_by_peer_total 5728
telemt_me_route_drop_no_conn_total 1862055
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2131198
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8324
telemt_desync_full_logged_total 2626
telemt_desync_suppressed_total 5698
telemt_desync_frames_bucket_total{bucket="1_2"} 2058
telemt_desync_frames_bucket_total{bucket="3_10"} 3020
telemt_desync_frames_bucket_total{bucket="gt_10"} 3246
telemt_pool_swap_total 31
telemt_me_writer_close_signal_drop_total 476
telemt_me_writer_removed_unexpected_total 6140
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 5513
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 623
telemt_user_connections_total{user="hello"} 2173269
telemt_user_connections_current{user="hello"} 976
telemt_user_octets_from_client{user="hello"} 35458972093 (33.02 GB)
telemt_user_octets_to_client{user="hello"} 610157806629 (568.25 GB)
telemt_user_msgs_from_client{user="hello"} 240837
telemt_user_msgs_to_client{user="hello"} 1741640
telemt_user_unique_ips_current{user="hello"} 411
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 99632.2 (27h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6260727
telemt_connections_bad_total 1042274
telemt_connections_current 1123
telemt_connections_me_current 1123
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 113266
telemt_upstream_connect_attempt_total 127337
telemt_upstream_connect_success_total 94054
telemt_upstream_connect_fail_total 33283
telemt_upstream_connect_attempts_per_request{bucket="1"} 127337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12403
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1433
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33283
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 78442
telemt_me_reconnect_success_total 12772
telemt_me_reader_eof_total 13758
telemt_me_idle_close_by_peer_total 13744
telemt_me_route_drop_no_conn_total 2794608
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4435673
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
telemt_desync_total 19497
telemt_desync_full_logged_total 6174
telemt_desync_suppressed_total 13323
telemt_desync_frames_bucket_total{bucket="1_2"} 3430
telemt_desync_frames_bucket_total{bucket="3_10"} 8025
telemt_desync_frames_bucket_total{bucket="gt_10"} 8042
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 13080
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 12747
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 308
telemt_user_connections_total{user="hello"} 4510887
telemt_user_connections_current{user="hello"} 1123
telemt_user_octets_from_client{user="hello"} 72429842300 (67.46 GB)
telemt_user_octets_to_client{user="hello"} 1737411139928 (1.58 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 505
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 45872.2 (12h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 707715
telemt_connections_bad_total 75184
telemt_connections_current 350
telemt_connections_me_current 350
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13006
telemt_upstream_connect_attempt_total 13502
telemt_upstream_connect_success_total 13172
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6875
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 6554
telemt_me_reconnect_success_total 6447
telemt_me_reader_eof_total 6762
telemt_me_idle_close_by_peer_total 6759
telemt_me_route_drop_no_conn_total 468631
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 581350
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
telemt_me_writer_removed_unexpected_total 6508
telemt_me_writer_restored_same_endpoint_total 6438
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 569496
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 7318791539 (6.82 GB)
telemt_user_octets_to_client{user="hello"} 144521648082 (134.60 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 45873.5 (12h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2011879
telemt_connections_bad_total 120004
telemt_connections_current 1163
telemt_connections_me_current 1163
telemt_handshake_timeouts_total 37371
telemt_upstream_connect_attempt_total 8130
telemt_upstream_connect_success_total 8071
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 8130
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4349
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3685
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 5830
telemt_me_reconnect_success_total 5788
telemt_me_reader_eof_total 6106
telemt_me_idle_close_by_peer_total 6106
telemt_me_route_drop_no_conn_total 741215
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1734311
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9198
telemt_desync_full_logged_total 2950
telemt_desync_suppressed_total 6248
telemt_desync_frames_bucket_total{bucket="1_2"} 1727
telemt_desync_frames_bucket_total{bucket="3_10"} 3227
telemt_desync_frames_bucket_total{bucket="gt_10"} 4244
telemt_pool_swap_total 45
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 5875
telemt_me_writer_restored_same_endpoint_total 5771
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 1733420
telemt_user_connections_current{user="hello"} 1163
telemt_user_octets_from_client{user="hello"} 29633343868 (27.60 GB)
telemt_user_octets_to_client{user="hello"} 878783621260 (818.43 GB)
telemt_user_unique_ips_current{user="hello"} 460
telemt_user_unique_ips_recent_window{user="hello"} 71
```