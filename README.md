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

# Server Metrics 2026-03-19 16:12:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 7701.6 (2h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 286672
telemt_connections_bad_total 8377
telemt_connections_current 1713
telemt_connections_direct_current 1713
telemt_relay_adaptive_promotions_total 79
telemt_relay_adaptive_demotions_total 23827
telemt_relay_adaptive_hard_promotions_total 78
telemt_handshake_timeouts_total 3247
telemt_upstream_connect_attempt_total 246179
telemt_upstream_connect_success_total 246055
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 246179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 235445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10495
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 246053
telemt_user_connections_current{user="hello"} 1713
telemt_user_octets_from_client{user="hello"} 5380504847 (5.01 GB)
telemt_user_octets_to_client{user="hello"} 48748057926 (45.40 GB)
telemt_user_msgs_from_client{user="hello"} 4877682
telemt_user_msgs_to_client{user="hello"} 5179916
telemt_user_unique_ips_current{user="hello"} 444
telemt_user_unique_ips_recent_window{user="hello"} 280
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 12574.7 (3h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1356427
telemt_connections_bad_total 60744
telemt_connections_current 4025
telemt_connections_me_current 4025
telemt_handshake_timeouts_total 26453
telemt_upstream_connect_attempt_total 3467
telemt_upstream_connect_success_total 3433
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 3467
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 996
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 5768
telemt_me_reconnect_success_total 1549
telemt_me_reader_eof_total 1682
telemt_me_idle_close_by_peer_total 1682
telemt_me_route_drop_no_conn_total 865605
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1099752
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4178
telemt_desync_full_logged_total 1287
telemt_desync_suppressed_total 2891
telemt_desync_frames_bucket_total{bucket="1_2"} 841
telemt_desync_frames_bucket_total{bucket="3_10"} 1626
telemt_desync_frames_bucket_total{bucket="gt_10"} 1711
telemt_pool_swap_total 6
telemt_me_writer_close_signal_drop_total 31
telemt_me_writer_removed_unexpected_total 1682
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 1494
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 1099920
telemt_user_connections_current{user="hello"} 4025
telemt_user_octets_from_client{user="hello"} 14148249246 (13.18 GB)
telemt_user_octets_to_client{user="hello"} 328985419474 (306.39 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1355
telemt_user_unique_ips_recent_window{user="hello"} 615
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 12553.1 (3h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1214491
telemt_connections_bad_total 147043
telemt_connections_current 2982
telemt_connections_me_current 2982
telemt_handshake_timeouts_total 12352
telemt_upstream_connect_attempt_total 2092
telemt_upstream_connect_success_total 2077
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 2092
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 935
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2332
telemt_me_reconnect_success_total 1419
telemt_me_reader_eof_total 1409
telemt_me_idle_close_by_peer_total 1408
telemt_me_route_drop_no_conn_total 952388
telemt_me_route_drop_channel_closed_total 82
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 916477
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3115
telemt_desync_full_logged_total 873
telemt_desync_suppressed_total 2242
telemt_desync_frames_bucket_total{bucket="1_2"} 847
telemt_desync_frames_bucket_total{bucket="3_10"} 1162
telemt_desync_frames_bucket_total{bucket="gt_10"} 1106
telemt_pool_swap_total 7
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 1399
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 1418
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 913663
telemt_user_connections_current{user="hello"} 2982
telemt_user_octets_from_client{user="hello"} 10815595096 (10.07 GB)
telemt_user_octets_to_client{user="hello"} 267482636692 (249.11 GB)
telemt_user_unique_ips_current{user="hello"} 1027
telemt_user_unique_ips_recent_window{user="hello"} 416
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 12540.6 (3h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1016401
telemt_connections_bad_total 52424
telemt_connections_current 2959
telemt_connections_me_current 2959
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 15237
telemt_upstream_connect_attempt_total 19048
telemt_upstream_connect_success_total 18166
telemt_upstream_connect_fail_total 882
telemt_upstream_connect_attempts_per_request{bucket="1"} 19048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2634
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 331
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 882
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 2951
telemt_me_reconnect_success_total 1570
telemt_me_reader_eof_total 1586
telemt_me_idle_close_by_peer_total 1585
telemt_me_route_drop_no_conn_total 683808
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 857267
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4005
telemt_desync_full_logged_total 1249
telemt_desync_suppressed_total 2756
telemt_desync_frames_bucket_total{bucket="1_2"} 1052
telemt_desync_frames_bucket_total{bucket="3_10"} 1478
telemt_desync_frames_bucket_total{bucket="gt_10"} 1475
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 147
telemt_me_writer_removed_unexpected_total 1853
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 1566
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 283
telemt_user_connections_total{user="hello"} 872647
telemt_user_connections_current{user="hello"} 2959
telemt_user_octets_from_client{user="hello"} 15848461249 (14.76 GB)
telemt_user_octets_to_client{user="hello"} 204889661850 (190.82 GB)
telemt_user_msgs_from_client{user="hello"} 40382
telemt_user_msgs_to_client{user="hello"} 85113
telemt_user_unique_ips_current{user="hello"} 1014
telemt_user_unique_ips_recent_window{user="hello"} 440
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 66264.0 (18h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4716634
telemt_connections_bad_total 831873
telemt_connections_current 3416
telemt_connections_me_current 3416
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 91438
telemt_upstream_connect_attempt_total 63715
telemt_upstream_connect_success_total 61225
telemt_upstream_connect_fail_total 2490
telemt_upstream_connect_attempts_per_request{bucket="1"} 63715
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7858
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2490
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 74120
telemt_me_reconnect_success_total 8719
telemt_me_reader_eof_total 9172
telemt_me_idle_close_by_peer_total 9169
telemt_me_route_drop_no_conn_total 2238070
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3277207
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
telemt_desync_total 14187
telemt_desync_full_logged_total 4322
telemt_desync_suppressed_total 9865
telemt_desync_frames_bucket_total{bucket="1_2"} 2369
telemt_desync_frames_bucket_total{bucket="3_10"} 6049
telemt_desync_frames_bucket_total{bucket="gt_10"} 5769
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 8943
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 8695
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 224
telemt_user_connections_total{user="hello"} 3325494
telemt_user_connections_current{user="hello"} 3416
telemt_user_octets_from_client{user="hello"} 52334867839 (48.74 GB)
telemt_user_octets_to_client{user="hello"} 1189076790744 (1.08 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1136
telemt_user_unique_ips_recent_window{user="hello"} 527
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 12506.1 (3h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 276670
telemt_connections_bad_total 22368
telemt_connections_current 924
telemt_connections_me_current 924
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 6904
telemt_upstream_connect_attempt_total 4977
telemt_upstream_connect_success_total 4840
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 4977
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2905
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 14
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 165
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_reconnect_attempts_total 1680
telemt_me_reconnect_success_total 1645
telemt_me_reader_eof_total 1654
telemt_me_idle_close_by_peer_total 1654
telemt_me_route_drop_no_conn_total 167978
telemt_me_route_drop_channel_closed_total 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 231198
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
telemt_desync_total 641
telemt_desync_full_logged_total 207
telemt_desync_suppressed_total 434
telemt_desync_frames_bucket_total{bucket="1_2"} 90
telemt_desync_frames_bucket_total{bucket="3_10"} 257
telemt_desync_frames_bucket_total{bucket="gt_10"} 294
telemt_pool_swap_total 8
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 58
telemt_me_writer_removed_unexpected_total 1625
telemt_me_writer_restored_same_endpoint_total 1636
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 179
telemt_me_async_recovery_trigger_total 1239
telemt_user_connections_total{user="hello"} 233792
telemt_user_connections_current{user="hello"} 924
telemt_user_octets_from_client{user="hello"} 3199317512 (2.98 GB)
telemt_user_octets_to_client{user="hello"} 61490864854 (57.27 GB)
telemt_user_msgs_from_client{user="hello"} 7378
telemt_user_msgs_to_client{user="hello"} 12667
telemt_user_unique_ips_current{user="hello"} 345
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 12505.1 (3h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 850580
telemt_connections_bad_total 55603
telemt_connections_current 3055
telemt_connections_me_current 3055
telemt_handshake_timeouts_total 13730
telemt_upstream_connect_attempt_total 2116
telemt_upstream_connect_success_total 2097
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 2116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 942
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 1453
telemt_me_reconnect_success_total 1431
telemt_me_reader_eof_total 1481
telemt_me_idle_close_by_peer_total 1481
telemt_me_route_drop_no_conn_total 358592
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 731945
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4025
telemt_desync_full_logged_total 1233
telemt_desync_suppressed_total 2792
telemt_desync_frames_bucket_total{bucket="1_2"} 798
telemt_desync_frames_bucket_total{bucket="3_10"} 1389
telemt_desync_frames_bucket_total{bucket="gt_10"} 1838
telemt_pool_swap_total 9
telemt_me_writer_close_signal_drop_total 29
telemt_me_writer_removed_unexpected_total 1462
telemt_me_writer_restored_same_endpoint_total 1414
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 731520
telemt_user_connections_current{user="hello"} 3055
telemt_user_octets_from_client{user="hello"} 10774938376 (10.03 GB)
telemt_user_octets_to_client{user="hello"} 315355579952 (293.70 GB)
telemt_user_unique_ips_current{user="hello"} 1017
telemt_user_unique_ips_recent_window{user="hello"} 412
```