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

# Server Metrics 2026-03-19 12:37:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 299.9 (0h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14259
telemt_connections_bad_total 489
telemt_connections_current 1546
telemt_connections_me_current 1546
telemt_handshake_timeouts_total 404
telemt_upstream_connect_attempt_total 84
telemt_upstream_connect_success_total 81
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 84
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 17
telemt_me_reconnect_success_total 17
telemt_me_reader_eof_total 1
telemt_me_idle_close_by_peer_total 1
telemt_me_route_drop_no_conn_total 5726
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12836
telemt_me_writer_pick_total{mode="p2c",result="full"} 27
telemt_me_writer_pick_total{mode="p2c",result="closed"} 60
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 41
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_me_writer_removed_unexpected_total 23
telemt_me_writer_restored_same_endpoint_total 7
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 306
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 12840
telemt_user_connections_current{user="hello"} 1546
telemt_user_octets_from_client{user="hello"} 128987752 (123.01 MB)
telemt_user_octets_to_client{user="hello"} 2491006500 (2.32 GB)
telemt_user_unique_ips_current{user="hello"} 550
telemt_user_unique_ips_recent_window{user="hello"} 235
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 53347.1 (14h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3804088
telemt_connections_bad_total 250367
telemt_connections_current 3746
telemt_connections_me_current 3746
telemt_handshake_timeouts_total 64682
telemt_upstream_connect_attempt_total 9922
telemt_upstream_connect_success_total 9737
telemt_upstream_connect_fail_total 185
telemt_upstream_connect_attempts_per_request{bucket="1"} 9922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4758
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 185
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 18412
telemt_me_reconnect_success_total 7000
telemt_me_reader_eof_total 7677
telemt_me_idle_close_by_peer_total 7676
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 3161029
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3201704
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12199
telemt_desync_full_logged_total 4072
telemt_desync_suppressed_total 8127
telemt_desync_frames_bucket_total{bucket="1_2"} 2354
telemt_desync_frames_bucket_total{bucket="3_10"} 4777
telemt_desync_frames_bucket_total{bucket="gt_10"} 5068
telemt_pool_swap_total 35
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 7481
telemt_me_refill_failed_total 356
telemt_me_writer_restored_same_endpoint_total 6975
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 481
telemt_user_connections_total{user="hello"} 3201290
telemt_user_connections_current{user="hello"} 3746
telemt_user_octets_from_client{user="hello"} 39718215876 (36.99 GB)
telemt_user_octets_to_client{user="hello"} 911041959752 (848.47 GB)
telemt_user_unique_ips_current{user="hello"} 1312
telemt_user_unique_ips_recent_window{user="hello"} 628
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 53344.4 (14h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2850423
telemt_connections_bad_total 324833
telemt_connections_current 3147
telemt_connections_me_current 3147
telemt_handshake_timeouts_total 54694
telemt_upstream_connect_attempt_total 9667
telemt_upstream_connect_success_total 9667
telemt_upstream_connect_attempts_per_request{bucket="1"} 9667
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4618
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 9318
telemt_me_reconnect_success_total 6930
telemt_me_reader_eof_total 7378
telemt_me_idle_close_by_peer_total 7376
telemt_me_route_drop_no_conn_total 1798411
telemt_me_route_drop_channel_closed_total 97
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2258281
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9486
telemt_desync_full_logged_total 2960
telemt_desync_suppressed_total 6526
telemt_desync_frames_bucket_total{bucket="1_2"} 2239
telemt_desync_frames_bucket_total{bucket="3_10"} 3450
telemt_desync_frames_bucket_total{bucket="gt_10"} 3797
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 7121
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 6914
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 191
telemt_user_connections_total{user="hello"} 2255855
telemt_user_connections_current{user="hello"} 3147
telemt_user_octets_from_client{user="hello"} 30544226128 (28.45 GB)
telemt_user_octets_to_client{user="hello"} 937631224856 (873.24 GB)
telemt_user_unique_ips_current{user="hello"} 1103
telemt_user_unique_ips_recent_window{user="hello"} 534
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 53397.5 (14h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3005137
telemt_connections_bad_total 147514
telemt_connections_current 3275
telemt_connections_me_current 3275
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 69222
telemt_upstream_connect_attempt_total 24787
telemt_upstream_connect_success_total 24254
telemt_upstream_connect_fail_total 533
telemt_upstream_connect_attempts_per_request{bucket="1"} 24787
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5868
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 435
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 533
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 11666
telemt_me_reconnect_success_total 6842
telemt_me_reader_eof_total 7270
telemt_me_idle_close_by_peer_total 7269
telemt_me_route_drop_no_conn_total 2377676
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2373061
telemt_me_writer_pick_total{mode="p2c",result="full"} 113
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_writer_pick_blocking_fallback_total 103
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7945
telemt_desync_full_logged_total 2643
telemt_desync_suppressed_total 5302
telemt_desync_frames_bucket_total{bucket="1_2"} 1696
telemt_desync_frames_bucket_total{bucket="3_10"} 3135
telemt_desync_frames_bucket_total{bucket="gt_10"} 3114
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 7460
telemt_me_refill_failed_total 138
telemt_me_writer_restored_same_endpoint_total 6818
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 311
telemt_me_writer_removed_unexpected_minus_restored_total 618
telemt_user_connections_total{user="hello"} 2385551
telemt_user_connections_current{user="hello"} 3275
telemt_user_octets_from_client{user="hello"} 25360195020 (23.62 GB)
telemt_user_octets_to_client{user="hello"} 591245139321 (550.64 GB)
telemt_user_msgs_from_client{user="hello"} 46376
telemt_user_msgs_to_client{user="hello"} 105213
telemt_user_unique_ips_current{user="hello"} 1020
telemt_user_unique_ips_recent_window{user="hello"} 441
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 53340.9 (14h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3527706
telemt_connections_bad_total 717730
telemt_connections_current 3554
telemt_connections_me_current 3554
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 68808
telemt_upstream_connect_attempt_total 61352
telemt_upstream_connect_success_total 58873
telemt_upstream_connect_fail_total 2479
telemt_upstream_connect_attempts_per_request{bucket="1"} 61352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6760
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1013
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2479
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 70061
telemt_me_reconnect_success_total 7012
telemt_me_reader_eof_total 7326
telemt_me_idle_close_by_peer_total 7323
telemt_me_route_drop_no_conn_total 1575197
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2346812
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
telemt_desync_total 10032
telemt_desync_full_logged_total 3117
telemt_desync_suppressed_total 6915
telemt_desync_frames_bucket_total{bucket="1_2"} 1837
telemt_desync_frames_bucket_total{bucket="3_10"} 4294
telemt_desync_frames_bucket_total{bucket="gt_10"} 3901
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 7128
telemt_me_refill_failed_total 1967
telemt_me_writer_restored_same_endpoint_total 6988
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 2395693
telemt_user_connections_current{user="hello"} 3554
telemt_user_octets_from_client{user="hello"} 37953559935 (35.35 GB)
telemt_user_octets_to_client{user="hello"} 878478312812 (818.15 GB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1150
telemt_user_unique_ips_recent_window{user="hello"} 553
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 53353.6 (14h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 592460
telemt_connections_bad_total 20751
telemt_connections_current 1023
telemt_connections_me_current 1023
telemt_handshake_timeouts_total 4916
telemt_upstream_connect_attempt_total 13165
telemt_upstream_connect_success_total 12818
telemt_upstream_connect_fail_total 347
telemt_upstream_connect_attempts_per_request{bucket="1"} 13165
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6518
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 347
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 17699
telemt_me_reconnect_success_total 10105
telemt_me_reader_eof_total 10760
telemt_me_idle_close_by_peer_total 10760
telemt_me_route_drop_no_conn_total 306152
telemt_me_route_drop_channel_closed_total 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 538367
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1358
telemt_desync_full_logged_total 471
telemt_desync_suppressed_total 887
telemt_desync_frames_bucket_total{bucket="1_2"} 261
telemt_desync_frames_bucket_total{bucket="3_10"} 561
telemt_desync_frames_bucket_total{bucket="gt_10"} 536
telemt_pool_swap_total 25
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 10437
telemt_me_refill_failed_total 235
telemt_me_writer_restored_same_endpoint_total 10074
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 332
telemt_user_connections_total{user="hello"} 538297
telemt_user_connections_current{user="hello"} 1023
telemt_user_octets_from_client{user="hello"} 8550279420 (7.96 GB)
telemt_user_octets_to_client{user="hello"} 190628556356 (177.54 GB)
telemt_user_unique_ips_current{user="hello"} 351
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 53343.4 (14h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2363534
telemt_connections_bad_total 186351
telemt_connections_current 3198
telemt_connections_me_current 3198
telemt_handshake_timeouts_total 75064
telemt_upstream_connect_attempt_total 10753
telemt_upstream_connect_success_total 10752
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10753
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5826
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4922
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 10530
telemt_me_reconnect_success_total 8021
telemt_me_reader_eof_total 8514
telemt_me_idle_close_by_peer_total 8513
telemt_me_route_drop_no_conn_total 1209838
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1993630
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10864
telemt_desync_full_logged_total 3433
telemt_desync_suppressed_total 7431
telemt_desync_frames_bucket_total{bucket="1_2"} 2078
telemt_desync_frames_bucket_total{bucket="3_10"} 4117
telemt_desync_frames_bucket_total{bucket="gt_10"} 4669
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 8203
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 8006
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 182
telemt_user_connections_total{user="hello"} 1992324
telemt_user_connections_current{user="hello"} 3198
telemt_user_octets_from_client{user="hello"} 25839363460 (24.06 GB)
telemt_user_octets_to_client{user="hello"} 881963172580 (821.39 GB)
telemt_user_unique_ips_current{user="hello"} 1039
telemt_user_unique_ips_recent_window{user="hello"} 433
```