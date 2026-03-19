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

# Server Metrics 2026-03-19 21:49:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 16324.7 (4h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 390973
telemt_connections_bad_total 19576
telemt_connections_current 749
telemt_connections_me_current 749
telemt_handshake_timeouts_total 5713
telemt_upstream_connect_attempt_total 2656
telemt_upstream_connect_success_total 2632
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 2656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1269
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1349
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 1791
telemt_me_reconnect_success_total 1778
telemt_me_reader_eof_total 1874
telemt_me_idle_close_by_peer_total 1874
telemt_me_route_drop_no_conn_total 118797
telemt_me_route_drop_channel_closed_total 49
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 311043
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1687
telemt_desync_full_logged_total 584
telemt_desync_suppressed_total 1103
telemt_desync_frames_bucket_total{bucket="1_2"} 354
telemt_desync_frames_bucket_total{bucket="3_10"} 521
telemt_desync_frames_bucket_total{bucket="gt_10"} 812
telemt_pool_swap_total 18
telemt_me_writer_close_signal_drop_total 32
telemt_me_writer_removed_unexpected_total 1818
telemt_me_writer_restored_same_endpoint_total 1765
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 311313
telemt_user_connections_current{user="hello"} 749
telemt_user_octets_from_client{user="hello"} 11112073688 (10.35 GB)
telemt_user_octets_to_client{user="hello"} 116193760408 (108.21 GB)
telemt_user_unique_ips_current{user="hello"} 289
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 32779.1 (9h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2719402
telemt_connections_bad_total 115942
telemt_connections_current 2004
telemt_connections_me_current 2004
telemt_handshake_timeouts_total 53571
telemt_upstream_connect_attempt_total 6738
telemt_upstream_connect_success_total 6632
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 6738
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2492
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 7973
telemt_me_reconnect_success_total 3743
telemt_me_reader_eof_total 4022
telemt_me_idle_close_by_peer_total 4022
telemt_me_route_drop_no_conn_total 1423697
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2320130
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10300
telemt_desync_full_logged_total 3344
telemt_desync_suppressed_total 6956
telemt_desync_frames_bucket_total{bucket="1_2"} 1922
telemt_desync_frames_bucket_total{bucket="3_10"} 4016
telemt_desync_frames_bucket_total{bucket="gt_10"} 4362
telemt_pool_swap_total 25
telemt_me_writer_close_signal_drop_total 42
telemt_me_writer_removed_unexpected_total 3910
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 3688
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 2320008
telemt_user_connections_current{user="hello"} 2004
telemt_user_octets_from_client{user="hello"} 36556870222 (34.05 GB)
telemt_user_octets_to_client{user="hello"} 825941782402 (769.22 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 808
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 32757.3 (9h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2650112
telemt_connections_bad_total 456882
telemt_connections_current 1432
telemt_connections_me_current 1432
telemt_handshake_timeouts_total 33207
telemt_upstream_connect_attempt_total 5116
telemt_upstream_connect_success_total 5074
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 5116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2438
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4337
telemt_me_reconnect_success_total 3411
telemt_me_reader_eof_total 3543
telemt_me_idle_close_by_peer_total 3542
telemt_me_route_drop_no_conn_total 1849714
telemt_me_route_drop_channel_closed_total 166
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1853968
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7136
telemt_desync_full_logged_total 2145
telemt_desync_suppressed_total 4991
telemt_desync_frames_bucket_total{bucket="1_2"} 1791
telemt_desync_frames_bucket_total{bucket="3_10"} 2713
telemt_desync_frames_bucket_total{bucket="gt_10"} 2632
telemt_pool_swap_total 30
telemt_me_writer_close_signal_drop_total 60
telemt_me_writer_removed_unexpected_total 3431
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3410
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 1849906
telemt_user_connections_current{user="hello"} 1432
telemt_user_octets_from_client{user="hello"} 28086395044 (26.16 GB)
telemt_user_octets_to_client{user="hello"} 675246086884 (628.87 GB)
telemt_user_unique_ips_current{user="hello"} 593
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 32745.1 (9h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2321575
telemt_connections_bad_total 95196
telemt_connections_current 1529
telemt_connections_me_current 1529
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 29192
telemt_upstream_connect_attempt_total 35344
telemt_upstream_connect_success_total 33619
telemt_upstream_connect_fail_total 1725
telemt_upstream_connect_attempts_per_request{bucket="1"} 35344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27747
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5405
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 448
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1725
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 6488
telemt_me_reconnect_success_total 3876
telemt_me_reader_eof_total 4015
telemt_me_idle_close_by_peer_total 4014
telemt_me_route_drop_no_conn_total 1812046
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1976051
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7928
telemt_desync_full_logged_total 2475
telemt_desync_suppressed_total 5453
telemt_desync_frames_bucket_total{bucket="1_2"} 1951
telemt_desync_frames_bucket_total{bucket="3_10"} 2885
telemt_desync_frames_bucket_total{bucket="gt_10"} 3092
telemt_pool_swap_total 19
telemt_me_writer_close_signal_drop_total 347
telemt_me_writer_removed_unexpected_total 4390
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 3872
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 514
telemt_user_connections_total{user="hello"} 2002984
telemt_user_connections_current{user="hello"} 1529
telemt_user_octets_from_client{user="hello"} 32991703924 (30.73 GB)
telemt_user_octets_to_client{user="hello"} 508884164411 (473.94 GB)
telemt_user_msgs_from_client{user="hello"} 69950
telemt_user_msgs_to_client{user="hello"} 147135
telemt_user_unique_ips_current{user="hello"} 568
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 86468.4 (24h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5993244
telemt_connections_bad_total 1031522
telemt_connections_current 1881
telemt_connections_me_current 1881
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 108594
telemt_upstream_connect_attempt_total 66677
telemt_upstream_connect_success_total 64171
telemt_upstream_connect_fail_total 2506
telemt_upstream_connect_attempts_per_request{bucket="1"} 66677
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53827
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9287
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1057
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2506
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 76092
telemt_me_reconnect_success_total 10674
telemt_me_reader_eof_total 11266
telemt_me_idle_close_by_peer_total 11263
telemt_me_route_drop_no_conn_total 2733399
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4251489
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
telemt_desync_total 18717
telemt_desync_full_logged_total 5815
telemt_desync_suppressed_total 12902
telemt_desync_frames_bucket_total{bucket="1_2"} 3250
telemt_desync_frames_bucket_total{bucket="3_10"} 7714
telemt_desync_frames_bucket_total{bucket="gt_10"} 7753
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 10937
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 10650
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 263
telemt_user_connections_total{user="hello"} 4299538
telemt_user_connections_current{user="hello"} 1881
telemt_user_octets_from_client{user="hello"} 66735286427 (62.15 GB)
telemt_user_octets_to_client{user="hello"} 1659577610640 (1.51 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 694
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 32708.3 (9h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 619935
telemt_connections_bad_total 48918
telemt_connections_current 429
telemt_connections_me_current 429
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 11857
telemt_upstream_connect_attempt_total 9184
telemt_upstream_connect_success_total 8971
telemt_upstream_connect_fail_total 213
telemt_upstream_connect_attempts_per_request{bucket="1"} 9184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5153
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 564
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 213
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 4395
telemt_me_reconnect_success_total 4316
telemt_me_reader_eof_total 4494
telemt_me_idle_close_by_peer_total 4492
telemt_me_route_drop_no_conn_total 419683
telemt_me_route_drop_channel_closed_total 143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 507901
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
telemt_desync_total 1348
telemt_desync_full_logged_total 504
telemt_desync_suppressed_total 844
telemt_desync_frames_bucket_total{bucket="1_2"} 207
telemt_desync_frames_bucket_total{bucket="3_10"} 553
telemt_desync_frames_bucket_total{bucket="gt_10"} 588
telemt_pool_swap_total 26
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 144
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 4355
telemt_me_writer_restored_same_endpoint_total 4307
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 512823
telemt_user_connections_current{user="hello"} 429
telemt_user_octets_from_client{user="hello"} 6778495872 (6.31 GB)
telemt_user_octets_to_client{user="hello"} 117218489526 (109.17 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 32709.7 (9h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1837706
telemt_connections_bad_total 108006
telemt_connections_current 1742
telemt_connections_me_current 1742
telemt_handshake_timeouts_total 33291
telemt_upstream_connect_attempt_total 5467
telemt_upstream_connect_success_total 5426
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 5467
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2469
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 3788
telemt_me_reconnect_success_total 3754
telemt_me_reader_eof_total 3952
telemt_me_idle_close_by_peer_total 3952
telemt_me_route_drop_no_conn_total 688113
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1593939
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8517
telemt_desync_full_logged_total 2680
telemt_desync_suppressed_total 5837
telemt_desync_frames_bucket_total{bucket="1_2"} 1573
telemt_desync_frames_bucket_total{bucket="3_10"} 2974
telemt_desync_frames_bucket_total{bucket="gt_10"} 3970
telemt_pool_swap_total 31
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 3823
telemt_me_writer_restored_same_endpoint_total 3737
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 1593087
telemt_user_connections_current{user="hello"} 1742
telemt_user_octets_from_client{user="hello"} 27128033524 (25.26 GB)
telemt_user_octets_to_client{user="hello"} 789497403056 (735.28 GB)
telemt_user_unique_ips_current{user="hello"} 614
telemt_user_unique_ips_recent_window{user="hello"} 148
```