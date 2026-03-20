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

# Server Metrics 2026-03-20 00:02:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 24276.0 (6h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 489823
telemt_connections_bad_total 31566
telemt_connections_current 826
telemt_connections_me_current 826
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 7365
telemt_upstream_connect_attempt_total 5265
telemt_upstream_connect_success_total 5193
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 5265
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2075
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 2894
telemt_me_reconnect_success_total 2865
telemt_me_reader_eof_total 2994
telemt_me_idle_close_by_peer_total 2993
telemt_me_route_drop_no_conn_total 143726
telemt_me_route_drop_channel_closed_total 55
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 387594
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1976
telemt_desync_full_logged_total 699
telemt_desync_suppressed_total 1277
telemt_desync_frames_bucket_total{bucket="1_2"} 410
telemt_desync_frames_bucket_total{bucket="3_10"} 648
telemt_desync_frames_bucket_total{bucket="gt_10"} 918
telemt_pool_swap_total 26
telemt_me_writer_close_signal_drop_total 39
telemt_me_writer_removed_unexpected_total 2882
telemt_me_writer_restored_same_endpoint_total 2852
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 389008
telemt_user_connections_current{user="hello"} 826
telemt_user_octets_from_client{user="hello"} 29058275012 (27.06 GB)
telemt_user_octets_to_client{user="hello"} 142635436269 (132.84 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 301
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 40730.6 (11h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2903804
telemt_connections_bad_total 123336
telemt_connections_current 1423
telemt_connections_me_current 1423
telemt_handshake_timeouts_total 61300
telemt_upstream_connect_attempt_total 8137
telemt_upstream_connect_success_total 8004
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 8137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4757
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3193
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 8958
telemt_me_reconnect_success_total 4722
telemt_me_reader_eof_total 5065
telemt_me_idle_close_by_peer_total 5065
telemt_me_route_drop_no_conn_total 1476436
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2484083
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10764
telemt_desync_full_logged_total 3559
telemt_desync_suppressed_total 7205
telemt_desync_frames_bucket_total{bucket="1_2"} 2019
telemt_desync_frames_bucket_total{bucket="3_10"} 4225
telemt_desync_frames_bucket_total{bucket="gt_10"} 4520
telemt_pool_swap_total 34
telemt_me_writer_close_signal_drop_total 51
telemt_me_writer_removed_unexpected_total 4906
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 4667
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 2483907
telemt_user_connections_current{user="hello"} 1423
telemt_user_octets_from_client{user="hello"} 38504271558 (35.86 GB)
telemt_user_octets_to_client{user="hello"} 898404783910 (836.70 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 637
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 40716.2 (11h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2831699
telemt_connections_bad_total 467780
telemt_connections_current 1130
telemt_connections_me_current 1130
telemt_handshake_timeouts_total 38416
telemt_upstream_connect_attempt_total 6479
telemt_upstream_connect_success_total 6430
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 6479
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3125
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5305
telemt_me_reconnect_success_total 4374
telemt_me_reader_eof_total 4575
telemt_me_idle_close_by_peer_total 4574
telemt_me_route_drop_no_conn_total 1893597
telemt_me_route_drop_channel_closed_total 170
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1966924
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7525
telemt_desync_full_logged_total 2274
telemt_desync_suppressed_total 5251
telemt_desync_frames_bucket_total{bucket="1_2"} 1852
telemt_desync_frames_bucket_total{bucket="3_10"} 2860
telemt_desync_frames_bucket_total{bucket="gt_10"} 2813
telemt_pool_swap_total 39
telemt_me_writer_close_signal_drop_total 64
telemt_me_writer_removed_unexpected_total 4415
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4373
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 1962672
telemt_user_connections_current{user="hello"} 1130
telemt_user_octets_from_client{user="hello"} 29373020576 (27.36 GB)
telemt_user_octets_to_client{user="hello"} 745401377224 (694.21 GB)
telemt_user_unique_ips_current{user="hello"} 488
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 40696.7 (11h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2466896
telemt_connections_bad_total 107141
telemt_connections_current 1073
telemt_connections_me_current 1073
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 30285
telemt_upstream_connect_attempt_total 53457
telemt_upstream_connect_success_total 49288
telemt_upstream_connect_fail_total 4169
telemt_upstream_connect_attempts_per_request{bucket="1"} 53457
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41788
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6955
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 520
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4169
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 7679
telemt_me_reconnect_success_total 4912
telemt_me_reader_eof_total 5095
telemt_me_idle_close_by_peer_total 5094
telemt_me_route_drop_no_conn_total 1846136
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2074522
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8180
telemt_desync_full_logged_total 2580
telemt_desync_suppressed_total 5600
telemt_desync_frames_bucket_total{bucket="1_2"} 2006
telemt_desync_frames_bucket_total{bucket="3_10"} 2974
telemt_desync_frames_bucket_total{bucket="gt_10"} 3200
telemt_pool_swap_total 26
telemt_me_writer_close_signal_drop_total 403
telemt_me_writer_removed_unexpected_total 5487
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 4908
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 575
telemt_user_connections_total{user="hello"} 2115675
telemt_user_connections_current{user="hello"} 1073
telemt_user_octets_from_client{user="hello"} 34838598075 (32.45 GB)
telemt_user_octets_to_client{user="hello"} 578828130679 (539.08 GB)
telemt_user_msgs_from_client{user="hello"} 239211
telemt_user_msgs_to_client{user="hello"} 1739348
telemt_user_unique_ips_current{user="hello"} 435
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 94420.1 (26h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6179577
telemt_connections_bad_total 1038169
telemt_connections_current 1060
telemt_connections_direct_current 1060
telemt_relay_adaptive_promotions_total 27
telemt_relay_adaptive_demotions_total 3535
telemt_relay_adaptive_hard_promotions_total 25
telemt_handshake_timeouts_total 111197
telemt_upstream_connect_attempt_total 123253
telemt_upstream_connect_success_total 89972
telemt_upstream_connect_fail_total 33281
telemt_upstream_connect_attempts_per_request{bucket="1"} 123253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 76714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11834
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1424
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33281
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 77763
telemt_me_reconnect_success_total 12098
telemt_me_reader_eof_total 13044
telemt_me_idle_close_by_peer_total 13030
telemt_me_route_drop_no_conn_total 2773284
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4367360
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
telemt_desync_total 19206
telemt_desync_full_logged_total 6047
telemt_desync_suppressed_total 13159
telemt_desync_frames_bucket_total{bucket="1_2"} 3355
telemt_desync_frames_bucket_total{bucket="3_10"} 7884
telemt_desync_frames_bucket_total{bucket="gt_10"} 7967
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 12400
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 12073
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 302
telemt_user_connections_total{user="hello"} 4439432
telemt_user_connections_current{user="hello"} 1060
telemt_user_octets_from_client{user="hello"} 68329990897 (63.64 GB)
telemt_user_octets_to_client{user="hello"} 1715469193854 (1.56 TB)
telemt_user_msgs_from_client{user="hello"} 727572
telemt_user_msgs_to_client{user="hello"} 2946209
telemt_user_unique_ips_current{user="hello"} 448
telemt_user_unique_ips_recent_window{user="hello"} 369
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 40660.0 (11h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 681091
telemt_connections_bad_total 69201
telemt_connections_current 336
telemt_connections_me_current 336
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12857
telemt_upstream_connect_attempt_total 12370
telemt_upstream_connect_success_total 12040
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 12370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4987
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6213
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 660
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 5637
telemt_me_reconnect_success_total 5532
telemt_me_reader_eof_total 5779
telemt_me_idle_close_by_peer_total 5776
telemt_me_route_drop_no_conn_total 458823
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 561688
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
telemt_pool_swap_total 35
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 150
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 5581
telemt_me_writer_restored_same_endpoint_total 5523
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 549832
telemt_user_connections_current{user="hello"} 336
telemt_user_octets_from_client{user="hello"} 7109872819 (6.62 GB)
telemt_user_octets_to_client{user="hello"} 133580956466 (124.41 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 40661.2 (11h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1958782
telemt_connections_bad_total 117936
telemt_connections_current 1147
telemt_connections_me_current 1147
telemt_handshake_timeouts_total 36336
telemt_upstream_connect_attempt_total 7101
telemt_upstream_connect_success_total 7047
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 7101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3249
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 5021
telemt_me_reconnect_success_total 4983
telemt_me_reader_eof_total 5258
telemt_me_idle_close_by_peer_total 5258
telemt_me_route_drop_no_conn_total 725656
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1686553
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8977
telemt_desync_full_logged_total 2870
telemt_desync_suppressed_total 6107
telemt_desync_frames_bucket_total{bucket="1_2"} 1648
telemt_desync_frames_bucket_total{bucket="3_10"} 3160
telemt_desync_frames_bucket_total{bucket="gt_10"} 4169
telemt_pool_swap_total 40
telemt_me_writer_close_signal_drop_total 37
telemt_me_writer_removed_unexpected_total 5063
telemt_me_writer_restored_same_endpoint_total 4966
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 1685688
telemt_user_connections_current{user="hello"} 1147
telemt_user_octets_from_client{user="hello"} 28510370412 (26.55 GB)
telemt_user_octets_to_client{user="hello"} 856287948012 (797.48 GB)
telemt_user_unique_ips_current{user="hello"} 482
telemt_user_unique_ips_recent_window{user="hello"} 90
```