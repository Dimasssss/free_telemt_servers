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

# Server Metrics 2026-03-19 20:32:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 11718.4 (3h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 326312
telemt_connections_bad_total 15445
telemt_connections_current 1001
telemt_connections_me_current 1001
telemt_handshake_timeouts_total 4850
telemt_upstream_connect_attempt_total 1796
telemt_upstream_connect_success_total 1780
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 1796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 918
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 1196
telemt_me_reconnect_success_total 1188
telemt_me_reader_eof_total 1246
telemt_me_idle_close_by_peer_total 1246
telemt_me_route_drop_no_conn_total 99029
telemt_me_route_drop_channel_closed_total 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 256255
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1260
telemt_desync_full_logged_total 427
telemt_desync_suppressed_total 833
telemt_desync_frames_bucket_total{bucket="1_2"} 266
telemt_desync_frames_bucket_total{bucket="3_10"} 365
telemt_desync_frames_bucket_total{bucket="gt_10"} 629
telemt_pool_swap_total 12
telemt_me_writer_close_signal_drop_total 30
telemt_me_writer_removed_unexpected_total 1217
telemt_me_writer_restored_same_endpoint_total 1175
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 256505
telemt_user_connections_current{user="hello"} 1001
telemt_user_octets_from_client{user="hello"} 10510632712 (9.79 GB)
telemt_user_octets_to_client{user="hello"} 92541373940 (86.19 GB)
telemt_user_unique_ips_current{user="hello"} 350
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 28173.5 (7h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2533994
telemt_connections_bad_total 108880
telemt_connections_current 2769
telemt_connections_me_current 2769
telemt_handshake_timeouts_total 48138
telemt_upstream_connect_attempt_total 5879
telemt_upstream_connect_success_total 5790
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 5879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2073
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 7347
telemt_me_reconnect_success_total 3119
telemt_me_reader_eof_total 3363
telemt_me_idle_close_by_peer_total 3363
telemt_me_route_drop_no_conn_total 1357667
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2152678
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9356
telemt_desync_full_logged_total 3057
telemt_desync_suppressed_total 6299
telemt_desync_frames_bucket_total{bucket="1_2"} 1720
telemt_desync_frames_bucket_total{bucket="3_10"} 3670
telemt_desync_frames_bucket_total{bucket="gt_10"} 3966
telemt_pool_swap_total 21
telemt_me_writer_close_signal_drop_total 38
telemt_me_writer_removed_unexpected_total 3281
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 3064
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 2152632
telemt_user_connections_current{user="hello"} 2769
telemt_user_octets_from_client{user="hello"} 32267551190 (30.05 GB)
telemt_user_octets_to_client{user="hello"} 759371475410 (707.22 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1027
telemt_user_unique_ips_recent_window{user="hello"} 336
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 28152.0 (7h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2379020
telemt_connections_bad_total 345457
telemt_connections_current 2254
telemt_connections_me_current 2254
telemt_handshake_timeouts_total 27500
telemt_upstream_connect_attempt_total 4363
telemt_upstream_connect_success_total 4333
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 4363
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2039
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3810
telemt_me_reconnect_success_total 2889
telemt_me_reader_eof_total 2989
telemt_me_idle_close_by_peer_total 2988
telemt_me_route_drop_no_conn_total 1799612
telemt_me_route_drop_channel_closed_total 162
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1743283
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6503
telemt_desync_full_logged_total 1942
telemt_desync_suppressed_total 4561
telemt_desync_frames_bucket_total{bucket="1_2"} 1675
telemt_desync_frames_bucket_total{bucket="3_10"} 2440
telemt_desync_frames_bucket_total{bucket="gt_10"} 2388
telemt_pool_swap_total 25
telemt_me_writer_close_signal_drop_total 56
telemt_me_writer_removed_unexpected_total 2898
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2888
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 1739638
telemt_user_connections_current{user="hello"} 2254
telemt_user_octets_from_client{user="hello"} 24825116696 (23.12 GB)
telemt_user_octets_to_client{user="hello"} 608574754304 (566.78 GB)
telemt_user_unique_ips_current{user="hello"} 784
telemt_user_unique_ips_recent_window{user="hello"} 266
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 28139.5 (7h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2170607
telemt_connections_bad_total 82439
telemt_connections_current 2006
telemt_connections_me_current 2006
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 27101
telemt_upstream_connect_attempt_total 31625
telemt_upstream_connect_success_total 30074
telemt_upstream_connect_fail_total 1551
telemt_upstream_connect_attempts_per_request{bucket="1"} 31625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24789
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4846
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 420
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1551
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 5873
telemt_me_reconnect_success_total 3331
telemt_me_reader_eof_total 3458
telemt_me_idle_close_by_peer_total 3457
telemt_me_route_drop_no_conn_total 1766650
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1856816
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7406
telemt_desync_full_logged_total 2317
telemt_desync_suppressed_total 5089
telemt_desync_frames_bucket_total{bucket="1_2"} 1848
telemt_desync_frames_bucket_total{bucket="3_10"} 2685
telemt_desync_frames_bucket_total{bucket="gt_10"} 2873
telemt_pool_swap_total 15
telemt_me_writer_close_signal_drop_total 291
telemt_me_writer_removed_unexpected_total 3794
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 3327
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 463
telemt_user_connections_total{user="hello"} 1881002
telemt_user_connections_current{user="hello"} 2006
telemt_user_octets_from_client{user="hello"} 31246708536 (29.10 GB)
telemt_user_octets_to_client{user="hello"} 451749039790 (420.72 GB)
telemt_user_msgs_from_client{user="hello"} 63004
telemt_user_msgs_to_client{user="hello"} 130023
telemt_user_unique_ips_current{user="hello"} 740
telemt_user_unique_ips_recent_window{user="hello"} 237
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 81862.9 (22h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5840630
telemt_connections_bad_total 1028640
telemt_connections_current 2549
telemt_connections_me_current 2549
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 106910
telemt_upstream_connect_attempt_total 65927
telemt_upstream_connect_success_total 63428
telemt_upstream_connect_fail_total 2499
telemt_upstream_connect_attempts_per_request{bucket="1"} 65927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8917
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1055
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2499
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 75587
telemt_me_reconnect_success_total 10171
telemt_me_reader_eof_total 10732
telemt_me_idle_close_by_peer_total 10729
telemt_me_route_drop_no_conn_total 2676756
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4111674
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
telemt_desync_total 18061
telemt_desync_full_logged_total 5603
telemt_desync_suppressed_total 12458
telemt_desync_frames_bucket_total{bucket="1_2"} 3082
telemt_desync_frames_bucket_total{bucket="3_10"} 7475
telemt_desync_frames_bucket_total{bucket="gt_10"} 7504
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 10427
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 10147
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 256
telemt_user_connections_total{user="hello"} 4159735
telemt_user_connections_current{user="hello"} 2549
telemt_user_octets_from_client{user="hello"} 64911091683 (60.45 GB)
telemt_user_octets_to_client{user="hello"} 1582428617964 (1.44 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 904
telemt_user_unique_ips_recent_window{user="hello"} 312
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 28103.0 (7h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 585492
telemt_connections_bad_total 45624
telemt_connections_current 565
telemt_connections_me_current 565
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 11328
telemt_upstream_connect_attempt_total 8289
telemt_upstream_connect_success_total 8092
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 8289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2709
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4651
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 552
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 3717
telemt_me_reconnect_success_total 3655
telemt_me_reader_eof_total 3791
telemt_me_idle_close_by_peer_total 3790
telemt_me_route_drop_no_conn_total 389246
telemt_me_route_drop_channel_closed_total 138
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 465815
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
telemt_desync_total 1194
telemt_desync_full_logged_total 384
telemt_desync_suppressed_total 810
telemt_desync_frames_bucket_total{bucket="1_2"} 191
telemt_desync_frames_bucket_total{bucket="3_10"} 484
telemt_desync_frames_bucket_total{bucket="gt_10"} 519
telemt_pool_swap_total 21
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 138
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 3686
telemt_me_writer_restored_same_endpoint_total 3646
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 484454
telemt_user_connections_current{user="hello"} 565
telemt_user_octets_from_client{user="hello"} 5451897704 (5.08 GB)
telemt_user_octets_to_client{user="hello"} 104757800798 (97.56 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 28104.3 (7h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1708252
telemt_connections_bad_total 101537
telemt_connections_current 2299
telemt_connections_me_current 2299
telemt_handshake_timeouts_total 27707
telemt_upstream_connect_attempt_total 4671
telemt_upstream_connect_success_total 4636
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 4671
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2090
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 3213
telemt_me_reconnect_success_total 3182
telemt_me_reader_eof_total 3344
telemt_me_idle_close_by_peer_total 3344
telemt_me_route_drop_no_conn_total 645550
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1485588
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7870
telemt_desync_full_logged_total 2431
telemt_desync_suppressed_total 5439
telemt_desync_frames_bucket_total{bucket="1_2"} 1475
telemt_desync_frames_bucket_total{bucket="3_10"} 2733
telemt_desync_frames_bucket_total{bucket="gt_10"} 3662
telemt_pool_swap_total 26
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 3241
telemt_me_writer_restored_same_endpoint_total 3165
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 1484813
telemt_user_connections_current{user="hello"} 2299
telemt_user_octets_from_client{user="hello"} 25247080744 (23.51 GB)
telemt_user_octets_to_client{user="hello"} 716738123092 (667.51 GB)
telemt_user_unique_ips_current{user="hello"} 784
telemt_user_unique_ips_recent_window{user="hello"} 208
```