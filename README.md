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

# Server Metrics 2026-03-19 18:42:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 5120.5 (1h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164165
telemt_connections_bad_total 5542
telemt_connections_current 1500
telemt_connections_me_current 1500
telemt_handshake_timeouts_total 1716
telemt_upstream_connect_attempt_total 760
telemt_upstream_connect_success_total 747
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 760
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 369
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 465
telemt_me_reconnect_success_total 461
telemt_me_reader_eof_total 471
telemt_me_idle_close_by_peer_total 471
telemt_me_route_drop_no_conn_total 52011
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 133344
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 605
telemt_desync_full_logged_total 200
telemt_desync_suppressed_total 405
telemt_desync_frames_bucket_total{bucket="1_2"} 139
telemt_desync_frames_bucket_total{bucket="3_10"} 181
telemt_desync_frames_bucket_total{bucket="gt_10"} 285
telemt_pool_swap_total 5
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 477
telemt_me_writer_restored_same_endpoint_total 448
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 133544
telemt_user_connections_current{user="hello"} 1500
telemt_user_octets_from_client{user="hello"} 2061574988 (1.92 GB)
telemt_user_octets_to_client{user="hello"} 45365691420 (42.25 GB)
telemt_user_unique_ips_current{user="hello"} 442
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 21576.3 (5h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2114324
telemt_connections_bad_total 99461
telemt_connections_current 3668
telemt_connections_me_current 3668
telemt_handshake_timeouts_total 39490
telemt_upstream_connect_attempt_total 4857
telemt_upstream_connect_success_total 4791
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 4857
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1601
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 6693
telemt_me_reconnect_success_total 2468
telemt_me_reader_eof_total 2663
telemt_me_idle_close_by_peer_total 2663
telemt_me_route_drop_no_conn_total 1192337
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1768226
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7184
telemt_desync_full_logged_total 2282
telemt_desync_suppressed_total 4902
telemt_desync_frames_bucket_total{bucket="1_2"} 1358
telemt_desync_frames_bucket_total{bucket="3_10"} 2848
telemt_desync_frames_bucket_total{bucket="gt_10"} 2978
telemt_pool_swap_total 14
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 2614
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 2413
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 1768181
telemt_user_connections_current{user="hello"} 3668
telemt_user_octets_from_client{user="hello"} 25610633954 (23.85 GB)
telemt_user_octets_to_client{user="hello"} 582386873658 (542.39 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1270
telemt_user_unique_ips_recent_window{user="hello"} 475
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 21554.5 (5h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1930793
telemt_connections_bad_total 228780
telemt_connections_current 2673
telemt_connections_me_current 2673
telemt_handshake_timeouts_total 22135
telemt_upstream_connect_attempt_total 3369
telemt_upstream_connect_success_total 3345
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 3369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1777
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1559
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3167
telemt_me_reconnect_success_total 2249
telemt_me_reader_eof_total 2297
telemt_me_idle_close_by_peer_total 2296
telemt_me_route_drop_no_conn_total 1681792
telemt_me_route_drop_channel_closed_total 104
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1469445
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4922
telemt_desync_full_logged_total 1468
telemt_desync_suppressed_total 3454
telemt_desync_frames_bucket_total{bucket="1_2"} 1254
telemt_desync_frames_bucket_total{bucket="3_10"} 1860
telemt_desync_frames_bucket_total{bucket="gt_10"} 1808
telemt_pool_swap_total 17
telemt_me_writer_close_signal_drop_total 50
telemt_me_writer_removed_unexpected_total 2244
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2248
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 1466182
telemt_user_connections_current{user="hello"} 2673
telemt_user_octets_from_client{user="hello"} 19327948360 (18.00 GB)
telemt_user_octets_to_client{user="hello"} 472463617920 (440.02 GB)
telemt_user_unique_ips_current{user="hello"} 924
telemt_user_unique_ips_recent_window{user="hello"} 322
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 21541.8 (5h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1810502
telemt_connections_bad_total 60538
telemt_connections_current 2677
telemt_connections_me_current 2677
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 24328
telemt_upstream_connect_attempt_total 25348
telemt_upstream_connect_success_total 24166
telemt_upstream_connect_fail_total 1182
telemt_upstream_connect_attempts_per_request{bucket="1"} 25348
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4036
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 353
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1182
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 5019
telemt_me_reconnect_success_total 2644
telemt_me_reader_eof_total 2736
telemt_me_idle_close_by_peer_total 2735
telemt_me_route_drop_no_conn_total 1583318
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1562492
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6115
telemt_desync_full_logged_total 1900
telemt_desync_suppressed_total 4215
telemt_desync_frames_bucket_total{bucket="1_2"} 1599
telemt_desync_frames_bucket_total{bucket="3_10"} 2248
telemt_desync_frames_bucket_total{bucket="gt_10"} 2268
telemt_pool_swap_total 9
telemt_me_writer_close_signal_drop_total 200
telemt_me_writer_removed_unexpected_total 3055
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 2640
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 411
telemt_user_connections_total{user="hello"} 1581829
telemt_user_connections_current{user="hello"} 2677
telemt_user_octets_from_client{user="hello"} 27232901105 (25.36 GB)
telemt_user_octets_to_client{user="hello"} 346509458333 (322.71 GB)
telemt_user_msgs_from_client{user="hello"} 49930
telemt_user_msgs_to_client{user="hello"} 93819
telemt_user_unique_ips_current{user="hello"} 930
telemt_user_unique_ips_recent_window{user="hello"} 310
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 75265.1 (20h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5500182
telemt_connections_bad_total 1007192
telemt_connections_current 3113
telemt_connections_me_current 3113
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 100513
telemt_upstream_connect_attempt_total 64984
telemt_upstream_connect_success_total 62491
telemt_upstream_connect_fail_total 2493
telemt_upstream_connect_attempts_per_request{bucket="1"} 64984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8444
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1049
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2493
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 74952
telemt_me_reconnect_success_total 9543
telemt_me_reader_eof_total 10060
telemt_me_idle_close_by_peer_total 10057
telemt_me_route_drop_no_conn_total 2528477
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3820390
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
telemt_desync_total 16729
telemt_desync_full_logged_total 5125
telemt_desync_suppressed_total 11604
telemt_desync_frames_bucket_total{bucket="1_2"} 2781
telemt_desync_frames_bucket_total{bucket="3_10"} 6961
telemt_desync_frames_bucket_total{bucket="gt_10"} 6987
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 9788
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 9519
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 3868517
telemt_user_connections_current{user="hello"} 3113
telemt_user_octets_from_client{user="hello"} 60551209211 (56.39 GB)
telemt_user_octets_to_client{user="hello"} 1422757615716 (1.29 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1095
telemt_user_unique_ips_recent_window{user="hello"} 457
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 21506.5 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 503845
telemt_connections_bad_total 35776
telemt_connections_current 612
telemt_connections_me_current 612
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 10267
telemt_upstream_connect_attempt_total 7173
telemt_upstream_connect_success_total 6976
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 7173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4010
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 548
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 424
telemt_me_reconnect_attempts_total 2946
telemt_me_reconnect_success_total 2889
telemt_me_reader_eof_total 2965
telemt_me_idle_close_by_peer_total 2964
telemt_me_route_drop_no_conn_total 358043
telemt_me_route_drop_channel_closed_total 125
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 398069
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
telemt_desync_total 1065
telemt_desync_full_logged_total 338
telemt_desync_suppressed_total 727
telemt_desync_frames_bucket_total{bucket="1_2"} 170
telemt_desync_frames_bucket_total{bucket="3_10"} 435
telemt_desync_frames_bucket_total{bucket="gt_10"} 460
telemt_pool_swap_total 13
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 131
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 2909
telemt_me_writer_restored_same_endpoint_total 2880
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 416722
telemt_user_connections_current{user="hello"} 612
telemt_user_octets_from_client{user="hello"} 4770560480 (4.44 GB)
telemt_user_octets_to_client{user="hello"} 87379158806 (81.38 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 228
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 21506.7 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1407095
telemt_connections_bad_total 88258
telemt_connections_current 2915
telemt_connections_me_current 2915
telemt_handshake_timeouts_total 24701
telemt_upstream_connect_attempt_total 3529
telemt_upstream_connect_success_total 3503
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 3529
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1619
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 2428
telemt_me_reconnect_success_total 2402
telemt_me_reader_eof_total 2518
telemt_me_idle_close_by_peer_total 2518
telemt_me_route_drop_no_conn_total 541388
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1217675
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6486
telemt_desync_full_logged_total 1986
telemt_desync_suppressed_total 4500
telemt_desync_frames_bucket_total{bucket="1_2"} 1246
telemt_desync_frames_bucket_total{bucket="3_10"} 2268
telemt_desync_frames_bucket_total{bucket="gt_10"} 2972
telemt_pool_swap_total 18
telemt_me_writer_close_signal_drop_total 31
telemt_me_writer_removed_unexpected_total 2451
telemt_me_writer_restored_same_endpoint_total 2385
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 1216968
telemt_user_connections_current{user="hello"} 2915
telemt_user_octets_from_client{user="hello"} 19246038236 (17.92 GB)
telemt_user_octets_to_client{user="hello"} 539364225728 (502.32 GB)
telemt_user_unique_ips_current{user="hello"} 970
telemt_user_unique_ips_recent_window{user="hello"} 356
```