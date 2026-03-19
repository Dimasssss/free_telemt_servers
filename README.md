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

# Server Metrics 2026-03-19 20:58:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 13262.7 (3h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 349687
telemt_connections_bad_total 16923
telemt_connections_current 858
telemt_connections_me_current 858
telemt_handshake_timeouts_total 5284
telemt_upstream_connect_attempt_total 2094
telemt_upstream_connect_success_total 2072
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 2094
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1063
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 1402
telemt_me_reconnect_success_total 1392
telemt_me_reader_eof_total 1464
telemt_me_idle_close_by_peer_total 1464
telemt_me_route_drop_no_conn_total 106827
telemt_me_route_drop_channel_closed_total 47
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 276179
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1412
telemt_desync_full_logged_total 485
telemt_desync_suppressed_total 927
telemt_desync_frames_bucket_total{bucket="1_2"} 297
telemt_desync_frames_bucket_total{bucket="3_10"} 406
telemt_desync_frames_bucket_total{bucket="gt_10"} 709
telemt_pool_swap_total 14
telemt_me_writer_close_signal_drop_total 31
telemt_me_writer_removed_unexpected_total 1425
telemt_me_writer_restored_same_endpoint_total 1379
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 276429
telemt_user_connections_current{user="hello"} 858
telemt_user_octets_from_client{user="hello"} 10719260464 (9.98 GB)
telemt_user_octets_to_client{user="hello"} 100940013892 (94.01 GB)
telemt_user_unique_ips_current{user="hello"} 323
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 29718.4 (8h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2603390
telemt_connections_bad_total 109954
telemt_connections_current 2561
telemt_connections_me_current 2561
telemt_handshake_timeouts_total 50531
telemt_upstream_connect_attempt_total 6090
telemt_upstream_connect_success_total 5996
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 6090
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3765
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2186
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 7510
telemt_me_reconnect_success_total 3282
telemt_me_reader_eof_total 3537
telemt_me_idle_close_by_peer_total 3537
telemt_me_route_drop_no_conn_total 1382371
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2216330
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9701
telemt_desync_full_logged_total 3180
telemt_desync_suppressed_total 6521
telemt_desync_frames_bucket_total{bucket="1_2"} 1794
telemt_desync_frames_bucket_total{bucket="3_10"} 3798
telemt_desync_frames_bucket_total{bucket="gt_10"} 4109
telemt_pool_swap_total 22
telemt_me_writer_close_signal_drop_total 38
telemt_me_writer_removed_unexpected_total 3447
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 3227
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 2216282
telemt_user_connections_current{user="hello"} 2561
telemt_user_octets_from_client{user="hello"} 34205987230 (31.86 GB)
telemt_user_octets_to_client{user="hello"} 783032896786 (729.26 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 940
telemt_user_unique_ips_recent_window{user="hello"} 308
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 29696.4 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2515055
telemt_connections_bad_total 418535
telemt_connections_current 1986
telemt_connections_me_current 1986
telemt_handshake_timeouts_total 29275
telemt_upstream_connect_attempt_total 4578
telemt_upstream_connect_success_total 4545
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 4578
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2166
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3979
telemt_me_reconnect_success_total 3057
telemt_me_reader_eof_total 3166
telemt_me_idle_close_by_peer_total 3165
telemt_me_route_drop_no_conn_total 1823296
telemt_me_route_drop_channel_closed_total 163
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1788674
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6717
telemt_desync_full_logged_total 2015
telemt_desync_suppressed_total 4702
telemt_desync_frames_bucket_total{bucket="1_2"} 1712
telemt_desync_frames_bucket_total{bucket="3_10"} 2528
telemt_desync_frames_bucket_total{bucket="gt_10"} 2477
telemt_pool_swap_total 26
telemt_me_writer_close_signal_drop_total 57
telemt_me_writer_removed_unexpected_total 3070
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3056
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 1784617
telemt_user_connections_current{user="hello"} 1986
telemt_user_octets_from_client{user="hello"} 25664098988 (23.90 GB)
telemt_user_octets_to_client{user="hello"} 632000882556 (588.60 GB)
telemt_user_unique_ips_current{user="hello"} 718
telemt_user_unique_ips_recent_window{user="hello"} 226
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 29684.1 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2228457
telemt_connections_bad_total 91094
telemt_connections_current 1875
telemt_connections_me_current 1875
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 27747
telemt_upstream_connect_attempt_total 31852
telemt_upstream_connect_success_total 30297
telemt_upstream_connect_fail_total 1555
telemt_upstream_connect_attempts_per_request{bucket="1"} 31852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4949
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 421
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1555
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 6055
telemt_me_reconnect_success_total 3511
telemt_me_reader_eof_total 3652
telemt_me_idle_close_by_peer_total 3651
telemt_me_route_drop_no_conn_total 1783788
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1901773
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7606
telemt_desync_full_logged_total 2367
telemt_desync_suppressed_total 5239
telemt_desync_frames_bucket_total{bucket="1_2"} 1889
telemt_desync_frames_bucket_total{bucket="3_10"} 2750
telemt_desync_frames_bucket_total{bucket="gt_10"} 2967
telemt_pool_swap_total 16
telemt_me_writer_close_signal_drop_total 292
telemt_me_writer_removed_unexpected_total 3979
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 3507
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 468
telemt_user_connections_total{user="hello"} 1925962
telemt_user_connections_current{user="hello"} 1875
telemt_user_octets_from_client{user="hello"} 31863369900 (29.68 GB)
telemt_user_octets_to_client{user="hello"} 470859514854 (438.52 GB)
telemt_user_msgs_from_client{user="hello"} 63004
telemt_user_msgs_to_client{user="hello"} 130023
telemt_user_unique_ips_current{user="hello"} 691
telemt_user_unique_ips_recent_window{user="hello"} 220
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 83407.3 (23h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5901888
telemt_connections_bad_total 1029551
telemt_connections_current 2381
telemt_connections_me_current 2381
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 107502
telemt_upstream_connect_attempt_total 66183
telemt_upstream_connect_success_total 63682
telemt_upstream_connect_fail_total 2501
telemt_upstream_connect_attempts_per_request{bucket="1"} 66183
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53573
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9053
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1056
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2501
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 75755
telemt_me_reconnect_success_total 10339
telemt_me_reader_eof_total 10914
telemt_me_idle_close_by_peer_total 10911
telemt_me_route_drop_no_conn_total 2700126
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4169230
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
telemt_desync_total 18285
telemt_desync_full_logged_total 5674
telemt_desync_suppressed_total 12611
telemt_desync_frames_bucket_total{bucket="1_2"} 3132
telemt_desync_frames_bucket_total{bucket="3_10"} 7583
telemt_desync_frames_bucket_total{bucket="gt_10"} 7570
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 10599
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 10315
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 260
telemt_user_connections_total{user="hello"} 4217287
telemt_user_connections_current{user="hello"} 2381
telemt_user_octets_from_client{user="hello"} 65652000059 (61.14 GB)
telemt_user_octets_to_client{user="hello"} 1613056897928 (1.47 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 852
telemt_user_unique_ips_recent_window{user="hello"} 255
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 29647.2 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 598648
telemt_connections_bad_total 46522
telemt_connections_current 549
telemt_connections_me_current 549
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 11532
telemt_upstream_connect_attempt_total 8528
telemt_upstream_connect_success_total 8331
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 8528
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4785
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 553
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 3913
telemt_me_reconnect_success_total 3850
telemt_me_reader_eof_total 3994
telemt_me_idle_close_by_peer_total 3993
telemt_me_route_drop_no_conn_total 393495
telemt_me_route_drop_channel_closed_total 141
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 476849
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
telemt_desync_total 1265
telemt_desync_full_logged_total 439
telemt_desync_suppressed_total 826
telemt_desync_frames_bucket_total{bucket="1_2"} 199
telemt_desync_frames_bucket_total{bucket="3_10"} 514
telemt_desync_frames_bucket_total{bucket="gt_10"} 552
telemt_pool_swap_total 22
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 139
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 3884
telemt_me_writer_restored_same_endpoint_total 3841
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 495469
telemt_user_connections_current{user="hello"} 549
telemt_user_octets_from_client{user="hello"} 5586408752 (5.20 GB)
telemt_user_octets_to_client{user="hello"} 107555087034 (100.17 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 29648.7 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1756213
telemt_connections_bad_total 103359
telemt_connections_current 2106
telemt_connections_me_current 2106
telemt_handshake_timeouts_total 30309
telemt_upstream_connect_attempt_total 4911
telemt_upstream_connect_success_total 4874
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 4911
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2212
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 3408
telemt_me_reconnect_success_total 3375
telemt_me_reader_eof_total 3546
telemt_me_idle_close_by_peer_total 3546
telemt_me_route_drop_no_conn_total 662032
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1526417
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8154
telemt_desync_full_logged_total 2531
telemt_desync_suppressed_total 5623
telemt_desync_frames_bucket_total{bucket="1_2"} 1515
telemt_desync_frames_bucket_total{bucket="3_10"} 2846
telemt_desync_frames_bucket_total{bucket="gt_10"} 3793
telemt_pool_swap_total 27
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 3437
telemt_me_writer_restored_same_endpoint_total 3358
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 1525572
telemt_user_connections_current{user="hello"} 2106
telemt_user_octets_from_client{user="hello"} 25995080944 (24.21 GB)
telemt_user_octets_to_client{user="hello"} 744563178372 (693.43 GB)
telemt_user_unique_ips_current{user="hello"} 728
telemt_user_unique_ips_recent_window{user="hello"} 200
```