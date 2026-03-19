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

# Server Metrics 2026-03-19 14:09:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 347.8 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32086
telemt_connections_bad_total 2
telemt_connections_current 103
telemt_connections_direct_current 103
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_demotions_total 77
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 25981
telemt_upstream_connect_attempt_total 1390
telemt_upstream_connect_success_total 1390
telemt_upstream_connect_attempts_per_request{bucket="1"} 1390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 129
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1388
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 12310809 (11.74 MB)
telemt_user_octets_to_client{user="hello"} 322311703 (307.38 MB)
telemt_user_msgs_from_client{user="hello"} 14559
telemt_user_msgs_to_client{user="hello"} 29611
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 5167.2 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 557815
telemt_connections_bad_total 17645
telemt_connections_current 3692
telemt_connections_me_current 3692
telemt_handshake_timeouts_total 9581
telemt_upstream_connect_attempt_total 2332
telemt_upstream_connect_success_total 2318
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2332
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1807
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 500
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 4999
telemt_me_reconnect_success_total 799
telemt_me_reader_eof_total 882
telemt_me_idle_close_by_peer_total 882
telemt_me_route_drop_no_conn_total 501005
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 495208
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1633
telemt_desync_full_logged_total 524
telemt_desync_suppressed_total 1109
telemt_desync_frames_bucket_total{bucket="1_2"} 300
telemt_desync_frames_bucket_total{bucket="3_10"} 616
telemt_desync_frames_bucket_total{bucket="gt_10"} 717
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 912
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 744
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 496047
telemt_user_connections_current{user="hello"} 3692
telemt_user_octets_from_client{user="hello"} 6725483210 (6.26 GB)
telemt_user_octets_to_client{user="hello"} 123603532426 (115.11 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1277
telemt_user_unique_ips_recent_window{user="hello"} 664
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 5145.6 (1h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 602062
telemt_connections_bad_total 61957
telemt_connections_current 3067
telemt_connections_me_current 3067
telemt_handshake_timeouts_total 6041
telemt_upstream_connect_attempt_total 824
telemt_upstream_connect_success_total 815
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 824
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 482
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 333
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 1422
telemt_me_reconnect_success_total 522
telemt_me_reader_eof_total 465
telemt_me_idle_close_by_peer_total 464
telemt_me_route_drop_no_conn_total 595939
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 451577
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1618
telemt_desync_full_logged_total 420
telemt_desync_suppressed_total 1198
telemt_desync_frames_bucket_total{bucket="1_2"} 435
telemt_desync_frames_bucket_total{bucket="3_10"} 617
telemt_desync_frames_bucket_total{bucket="gt_10"} 566
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 28
telemt_me_writer_removed_unexpected_total 479
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 521
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 449195
telemt_user_connections_current{user="hello"} 3067
telemt_user_octets_from_client{user="hello"} 4157093144 (3.87 GB)
telemt_user_octets_to_client{user="hello"} 111562023288 (103.90 GB)
telemt_user_unique_ips_current{user="hello"} 1052
telemt_user_unique_ips_recent_window{user="hello"} 467
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 5133.4 (1h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 446827
telemt_connections_bad_total 38939
telemt_connections_current 3007
telemt_connections_me_current 3007
telemt_handshake_timeouts_total 7004
telemt_upstream_connect_attempt_total 4364
telemt_upstream_connect_success_total 4195
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 4364
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 503
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 609
telemt_me_reconnect_success_total 575
telemt_me_reader_eof_total 553
telemt_me_idle_close_by_peer_total 552
telemt_me_route_drop_no_conn_total 297932
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 363317
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1619
telemt_desync_full_logged_total 526
telemt_desync_suppressed_total 1093
telemt_desync_frames_bucket_total{bucket="1_2"} 317
telemt_desync_frames_bucket_total{bucket="3_10"} 612
telemt_desync_frames_bucket_total{bucket="gt_10"} 690
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 25
telemt_me_writer_removed_unexpected_total 578
telemt_me_writer_restored_same_endpoint_total 572
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 366230
telemt_user_connections_current{user="hello"} 3007
telemt_user_octets_from_client{user="hello"} 6295859839 (5.86 GB)
telemt_user_octets_to_client{user="hello"} 84235023926 (78.45 GB)
telemt_user_msgs_from_client{user="hello"} 5613
telemt_user_msgs_to_client{user="hello"} 6373
telemt_user_unique_ips_current{user="hello"} 980
telemt_user_unique_ips_recent_window{user="hello"} 473
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 58856.5 (16h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4049699
telemt_connections_bad_total 766334
telemt_connections_current 3660
telemt_connections_me_current 3660
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 79279
telemt_upstream_connect_attempt_total 62337
telemt_upstream_connect_success_total 59853
telemt_upstream_connect_fail_total 2484
telemt_upstream_connect_attempts_per_request{bucket="1"} 62337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51614
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7222
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1017
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2484
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 71729
telemt_me_reconnect_success_total 7709
telemt_me_reader_eof_total 8079
telemt_me_idle_close_by_peer_total 8076
telemt_me_route_drop_no_conn_total 1937563
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2769782
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
telemt_desync_total 11982
telemt_desync_full_logged_total 3693
telemt_desync_suppressed_total 8289
telemt_desync_frames_bucket_total{bucket="1_2"} 2072
telemt_desync_frames_bucket_total{bucket="3_10"} 5141
telemt_desync_frames_bucket_total{bucket="gt_10"} 4769
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 7874
telemt_me_refill_failed_total 1997
telemt_me_writer_restored_same_endpoint_total 7685
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 2818477
telemt_user_connections_current{user="hello"} 3660
telemt_user_octets_from_client{user="hello"} 45235568195 (42.13 GB)
telemt_user_octets_to_client{user="hello"} 1005620598344 (936.56 GB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1159
telemt_user_unique_ips_recent_window{user="hello"} 624
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 5097.7 (1h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123801
telemt_connections_bad_total 5706
telemt_connections_current 980
telemt_connections_me_current 980
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 4850
telemt_upstream_connect_attempt_total 3527
telemt_upstream_connect_success_total 3390
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 3527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2051
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_reconnect_attempts_total 586
telemt_me_reconnect_success_total 562
telemt_me_reader_eof_total 524
telemt_me_idle_close_by_peer_total 524
telemt_me_route_drop_no_conn_total 93258
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 105261
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
telemt_desync_total 231
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 151
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 97
telemt_desync_frames_bucket_total{bucket="gt_10"} 96
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 525
telemt_me_writer_restored_same_endpoint_total 553
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 179
telemt_me_async_recovery_trigger_total 1239
telemt_user_connections_total{user="hello"} 107899
telemt_user_connections_current{user="hello"} 980
telemt_user_octets_from_client{user="hello"} 1482331908 (1.38 GB)
telemt_user_octets_to_client{user="hello"} 25542599254 (23.79 GB)
telemt_user_msgs_from_client{user="hello"} 7378
telemt_user_msgs_to_client{user="hello"} 12667
telemt_user_unique_ips_current{user="hello"} 361
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 5098.0 (1h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 354435
telemt_connections_bad_total 27657
telemt_connections_current 3162
telemt_connections_me_current 3162
telemt_handshake_timeouts_total 6399
telemt_upstream_connect_attempt_total 839
telemt_upstream_connect_success_total 834
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 839
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 379
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 547
telemt_me_reconnect_success_total 535
telemt_me_reader_eof_total 537
telemt_me_idle_close_by_peer_total 537
telemt_me_route_drop_no_conn_total 119922
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 308984
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1559
telemt_desync_full_logged_total 465
telemt_desync_suppressed_total 1094
telemt_desync_frames_bucket_total{bucket="1_2"} 262
telemt_desync_frames_bucket_total{bucket="3_10"} 519
telemt_desync_frames_bucket_total{bucket="gt_10"} 778
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 24
telemt_me_writer_removed_unexpected_total 553
telemt_me_writer_restored_same_endpoint_total 518
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 308743
telemt_user_connections_current{user="hello"} 3162
telemt_user_octets_from_client{user="hello"} 3575745008 (3.33 GB)
telemt_user_octets_to_client{user="hello"} 127288836812 (118.55 GB)
telemt_user_unique_ips_current{user="hello"} 1058
telemt_user_unique_ips_recent_window{user="hello"} 462
```