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

# Server Metrics 2026-03-19 21:08:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 13875.2 (3h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 359505
telemt_connections_bad_total 17457
telemt_connections_current 900
telemt_connections_me_current 900
telemt_handshake_timeouts_total 5373
telemt_upstream_connect_attempt_total 2221
telemt_upstream_connect_success_total 2199
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 2221
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1126
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 1486
telemt_me_reconnect_success_total 1476
telemt_me_reader_eof_total 1557
telemt_me_idle_close_by_peer_total 1557
telemt_me_route_drop_no_conn_total 109666
telemt_me_route_drop_channel_closed_total 47
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 284568
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1467
telemt_desync_full_logged_total 509
telemt_desync_suppressed_total 958
telemt_desync_frames_bucket_total{bucket="1_2"} 303
telemt_desync_frames_bucket_total{bucket="3_10"} 430
telemt_desync_frames_bucket_total{bucket="gt_10"} 734
telemt_pool_swap_total 15
telemt_me_writer_close_signal_drop_total 31
telemt_me_writer_removed_unexpected_total 1511
telemt_me_writer_restored_same_endpoint_total 1463
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 284819
telemt_user_connections_current{user="hello"} 900
telemt_user_octets_from_client{user="hello"} 10779438864 (10.04 GB)
telemt_user_octets_to_client{user="hello"} 104483577656 (97.31 GB)
telemt_user_unique_ips_current{user="hello"} 309
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 30329.6 (8h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2631467
telemt_connections_bad_total 111395
telemt_connections_current 2552
telemt_connections_me_current 2552
telemt_handshake_timeouts_total 51084
telemt_upstream_connect_attempt_total 6219
telemt_upstream_connect_success_total 6123
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 6219
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2252
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 7593
telemt_me_reconnect_success_total 3365
telemt_me_reader_eof_total 3625
telemt_me_idle_close_by_peer_total 3625
telemt_me_route_drop_no_conn_total 1391676
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2241407
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9839
telemt_desync_full_logged_total 3218
telemt_desync_suppressed_total 6621
telemt_desync_frames_bucket_total{bucket="1_2"} 1823
telemt_desync_frames_bucket_total{bucket="3_10"} 3850
telemt_desync_frames_bucket_total{bucket="gt_10"} 4166
telemt_pool_swap_total 23
telemt_me_writer_close_signal_drop_total 38
telemt_me_writer_removed_unexpected_total 3530
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 3310
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 2241345
telemt_user_connections_current{user="hello"} 2552
telemt_user_octets_from_client{user="hello"} 34461053118 (32.09 GB)
telemt_user_octets_to_client{user="hello"} 793510645466 (739.01 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 935
telemt_user_unique_ips_recent_window{user="hello"} 283
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 30307.9 (8h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2569093
telemt_connections_bad_total 450519
telemt_connections_current 1828
telemt_connections_me_current 1828
telemt_handshake_timeouts_total 30437
telemt_upstream_connect_attempt_total 4706
telemt_upstream_connect_success_total 4671
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 4706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2426
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2230
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4063
telemt_me_reconnect_success_total 3138
telemt_me_reader_eof_total 3251
telemt_me_idle_close_by_peer_total 3250
telemt_me_route_drop_no_conn_total 1829816
telemt_me_route_drop_channel_closed_total 164
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1804295
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6826
telemt_desync_full_logged_total 2041
telemt_desync_suppressed_total 4785
telemt_desync_frames_bucket_total{bucket="1_2"} 1733
telemt_desync_frames_bucket_total{bucket="3_10"} 2568
telemt_desync_frames_bucket_total{bucket="gt_10"} 2525
telemt_pool_swap_total 27
telemt_me_writer_close_signal_drop_total 59
telemt_me_writer_removed_unexpected_total 3152
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3137
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 1800234
telemt_user_connections_current{user="hello"} 1828
telemt_user_octets_from_client{user="hello"} 25879087852 (24.10 GB)
telemt_user_octets_to_client{user="hello"} 643727000628 (599.52 GB)
telemt_user_unique_ips_current{user="hello"} 684
telemt_user_unique_ips_recent_window{user="hello"} 202
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 30295.6 (8h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2247035
telemt_connections_bad_total 91164
telemt_connections_current 1926
telemt_connections_me_current 1926
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 27919
telemt_upstream_connect_attempt_total 31973
telemt_upstream_connect_success_total 30413
telemt_upstream_connect_fail_total 1560
telemt_upstream_connect_attempts_per_request{bucket="1"} 31973
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24968
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5005
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 421
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1560
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 6131
telemt_me_reconnect_success_total 3584
telemt_me_reader_eof_total 3727
telemt_me_idle_close_by_peer_total 3726
telemt_me_route_drop_no_conn_total 1792015
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1918804
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7719
telemt_desync_full_logged_total 2405
telemt_desync_suppressed_total 5314
telemt_desync_frames_bucket_total{bucket="1_2"} 1910
telemt_desync_frames_bucket_total{bucket="3_10"} 2803
telemt_desync_frames_bucket_total{bucket="gt_10"} 3006
telemt_pool_swap_total 17
telemt_me_writer_close_signal_drop_total 292
telemt_me_writer_removed_unexpected_total 4052
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 3580
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 468
telemt_user_connections_total{user="hello"} 1942974
telemt_user_connections_current{user="hello"} 1926
telemt_user_octets_from_client{user="hello"} 32358155484 (30.14 GB)
telemt_user_octets_to_client{user="hello"} 480226044222 (447.25 GB)
telemt_user_msgs_from_client{user="hello"} 63004
telemt_user_msgs_to_client{user="hello"} 130023
telemt_user_unique_ips_current{user="hello"} 668
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 84018.8 (23h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5923647
telemt_connections_bad_total 1029910
telemt_connections_current 2333
telemt_connections_me_current 2333
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 107745
telemt_upstream_connect_attempt_total 66291
telemt_upstream_connect_success_total 63790
telemt_upstream_connect_fail_total 2501
telemt_upstream_connect_attempts_per_request{bucket="1"} 66291
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9107
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1056
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2501
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 75820
telemt_me_reconnect_success_total 10404
telemt_me_reader_eof_total 10983
telemt_me_idle_close_by_peer_total 10980
telemt_me_route_drop_no_conn_total 2709261
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4189476
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
telemt_desync_total 18380
telemt_desync_full_logged_total 5710
telemt_desync_suppressed_total 12670
telemt_desync_frames_bucket_total{bucket="1_2"} 3148
telemt_desync_frames_bucket_total{bucket="3_10"} 7612
telemt_desync_frames_bucket_total{bucket="gt_10"} 7620
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 10664
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 10380
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 260
telemt_user_connections_total{user="hello"} 4237529
telemt_user_connections_current{user="hello"} 2333
telemt_user_octets_from_client{user="hello"} 65945979727 (61.42 GB)
telemt_user_octets_to_client{user="hello"} 1625711559564 (1.48 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 814
telemt_user_unique_ips_recent_window{user="hello"} 272
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 30258.8 (8h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 603516
telemt_connections_bad_total 47195
telemt_connections_current 581
telemt_connections_me_current 581
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 11606
telemt_upstream_connect_attempt_total 8672
telemt_upstream_connect_success_total 8475
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 8672
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2875
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4867
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 553
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 4014
telemt_me_reconnect_success_total 3951
telemt_me_reader_eof_total 4106
telemt_me_idle_close_by_peer_total 4105
telemt_me_route_drop_no_conn_total 395923
telemt_me_route_drop_channel_closed_total 143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 481074
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
telemt_desync_total 1298
telemt_desync_full_logged_total 466
telemt_desync_suppressed_total 832
telemt_desync_frames_bucket_total{bucket="1_2"} 201
telemt_desync_frames_bucket_total{bucket="3_10"} 529
telemt_desync_frames_bucket_total{bucket="gt_10"} 568
telemt_pool_swap_total 23
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 139
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 3986
telemt_me_writer_restored_same_endpoint_total 3942
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 499254
telemt_user_connections_current{user="hello"} 581
telemt_user_octets_from_client{user="hello"} 6593544924 (6.14 GB)
telemt_user_octets_to_client{user="hello"} 109641696678 (102.11 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 30260.1 (8h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1774493
telemt_connections_bad_total 104527
telemt_connections_current 2026
telemt_connections_me_current 2026
telemt_handshake_timeouts_total 30904
telemt_upstream_connect_attempt_total 5043
telemt_upstream_connect_success_total 5005
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 5043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2276
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 3496
telemt_me_reconnect_success_total 3463
telemt_me_reader_eof_total 3639
telemt_me_idle_close_by_peer_total 3639
telemt_me_route_drop_no_conn_total 668049
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1542126
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8264
telemt_desync_full_logged_total 2575
telemt_desync_suppressed_total 5689
telemt_desync_frames_bucket_total{bucket="1_2"} 1533
telemt_desync_frames_bucket_total{bucket="3_10"} 2888
telemt_desync_frames_bucket_total{bucket="gt_10"} 3843
telemt_pool_swap_total 28
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 3526
telemt_me_writer_restored_same_endpoint_total 3446
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 1541280
telemt_user_connections_current{user="hello"} 2026
telemt_user_octets_from_client{user="hello"} 26317207712 (24.51 GB)
telemt_user_octets_to_client{user="hello"} 754383463088 (702.57 GB)
telemt_user_unique_ips_current{user="hello"} 712
telemt_user_unique_ips_recent_window{user="hello"} 207
```