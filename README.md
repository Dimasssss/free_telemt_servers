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

# Server Metrics 2026-03-18 20:15:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 17401.6 (4h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 431704
telemt_connections_bad_total 25129
telemt_handshake_timeouts_total 9304
telemt_upstream_connect_attempt_total 3112
telemt_upstream_connect_success_total 3109
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1527
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 135
telemt_me_reconnect_attempts_total 2219
telemt_me_reconnect_success_total 2206
telemt_me_reader_eof_total 2301
telemt_me_idle_close_by_peer_total 2301
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 181876
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 372825
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2213
telemt_desync_full_logged_total 638
telemt_desync_suppressed_total 1575
telemt_desync_frames_bucket_total{bucket="1_2"} 522
telemt_desync_frames_bucket_total{bucket="3_10"} 706
telemt_desync_frames_bucket_total{bucket="gt_10"} 985
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2250
telemt_me_writer_restored_same_endpoint_total 2188
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 372645
telemt_user_connections_current{user="hello"} 1019
telemt_user_octets_from_client{user="hello"} 7331810668 (6.83 GB)
telemt_user_octets_to_client{user="hello"} 135155411620 (125.87 GB)
telemt_user_unique_ips_current{user="hello"} 364
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 22230.0 (6h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2043852
telemt_connections_bad_total 142223
telemt_connections_current 3051
telemt_connections_me_current 3051
telemt_handshake_timeouts_total 35281
telemt_upstream_connect_attempt_total 3489
telemt_upstream_connect_success_total 3470
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 3489
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1827
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1616
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 2361
telemt_me_reconnect_success_total 2344
telemt_me_reader_eof_total 2373
telemt_me_idle_close_by_peer_total 2372
telemt_me_route_drop_no_conn_total 1800818
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1768442
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6189
telemt_desync_full_logged_total 1999
telemt_desync_suppressed_total 4190
telemt_desync_frames_bucket_total{bucket="1_2"} 1072
telemt_desync_frames_bucket_total{bucket="3_10"} 2458
telemt_desync_frames_bucket_total{bucket="gt_10"} 2659
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 2306
telemt_me_writer_restored_same_endpoint_total 2342
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1763793
telemt_user_connections_current{user="hello"} 3051
telemt_user_octets_from_client{user="hello"} 27107272644 (25.25 GB)
telemt_user_octets_to_client{user="hello"} 594224274476 (553.41 GB)
telemt_user_unique_ips_current{user="hello"} 1072
telemt_user_unique_ips_recent_window{user="hello"} 356
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 22158.4 (6h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1557235
telemt_connections_bad_total 127726
telemt_connections_current 2711
telemt_connections_me_current 2711
telemt_handshake_timeouts_total 36005
telemt_upstream_connect_attempt_total 3181
telemt_upstream_connect_success_total 3164
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 3181
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1498
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 2053
telemt_me_reconnect_success_total 2035
telemt_me_reader_eof_total 2162
telemt_me_idle_close_by_peer_total 2162
telemt_me_route_drop_no_conn_total 631410
telemt_me_route_drop_channel_closed_total 60
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1250849
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6025
telemt_desync_full_logged_total 1849
telemt_desync_suppressed_total 4176
telemt_desync_frames_bucket_total{bucket="1_2"} 1514
telemt_desync_frames_bucket_total{bucket="3_10"} 2272
telemt_desync_frames_bucket_total{bucket="gt_10"} 2239
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 2086
telemt_me_writer_restored_same_endpoint_total 2018
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 1250049
telemt_user_connections_current{user="hello"} 2711
telemt_user_octets_from_client{user="hello"} 26889747712 (25.04 GB)
telemt_user_octets_to_client{user="hello"} 623783018580 (580.94 GB)
telemt_user_unique_ips_current{user="hello"} 907
telemt_user_unique_ips_recent_window{user="hello"} 310
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 22873.0 (6h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2194512
telemt_connections_bad_total 60991
telemt_connections_current 2277
telemt_connections_me_current 2277
telemt_handshake_timeouts_total 22044
telemt_upstream_connect_attempt_total 3464
telemt_upstream_connect_success_total 3428
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 3464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1636
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 2274
telemt_me_reconnect_success_total 2247
telemt_me_reader_eof_total 2339
telemt_me_idle_close_by_peer_total 2338
telemt_me_route_drop_no_conn_total 3696140
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1960600
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7403
telemt_desync_full_logged_total 1918
telemt_desync_suppressed_total 5485
telemt_desync_frames_bucket_total{bucket="1_2"} 1608
telemt_desync_frames_bucket_total{bucket="3_10"} 3429
telemt_desync_frames_bucket_total{bucket="gt_10"} 2366
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 2263
telemt_me_writer_restored_same_endpoint_total 2236
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 1960507
telemt_user_connections_current{user="hello"} 2277
telemt_user_octets_from_client{user="hello"} 18367469840 (17.11 GB)
telemt_user_octets_to_client{user="hello"} 340218054660 (316.85 GB)
telemt_user_unique_ips_current{user="hello"} 791
telemt_user_unique_ips_recent_window{user="hello"} 263
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 17387.9 (4h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1231663
telemt_connections_bad_total 220531
telemt_handshake_timeouts_total 11771
telemt_upstream_connect_attempt_total 3181
telemt_upstream_connect_success_total 3085
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 3181
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1434
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 75
telemt_me_reconnect_attempts_total 5431
telemt_me_reconnect_success_total 2182
telemt_me_reader_eof_total 2343
telemt_me_idle_close_by_peer_total 2343
telemt_me_route_drop_no_conn_total 521012
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 903449
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3245
telemt_desync_full_logged_total 1171
telemt_desync_suppressed_total 2074
telemt_desync_frames_bucket_total{bucket="1_2"} 596
telemt_desync_frames_bucket_total{bucket="3_10"} 1118
telemt_desync_frames_bucket_total{bucket="gt_10"} 1531
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2321
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 2156
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 902810
telemt_user_connections_current{user="hello"} 2723
telemt_user_octets_from_client{user="hello"} 15693493472 (14.62 GB)
telemt_user_octets_to_client{user="hello"} 435174346028 (405.29 GB)
telemt_user_unique_ips_current{user="hello"} 959
telemt_user_unique_ips_recent_window{user="hello"} 327
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 22321.2 (6h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 355337
telemt_connections_bad_total 10683
telemt_connections_current 628
telemt_connections_me_current 628
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 4020
telemt_upstream_connect_attempt_total 7872
telemt_upstream_connect_success_total 7840
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 7872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3762
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 332358
telemt_me_reconnect_success_total 2888
telemt_me_reader_eof_total 2949
telemt_me_idle_close_by_peer_total 2949
telemt_me_route_drop_no_conn_total 213686
telemt_me_route_drop_channel_closed_total 103
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 315794
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 658
telemt_desync_full_logged_total 241
telemt_desync_suppressed_total 417
telemt_desync_frames_bucket_total{bucket="1_2"} 150
telemt_desync_frames_bucket_total{bucket="3_10"} 254
telemt_desync_frames_bucket_total{bucket="gt_10"} 254
telemt_pool_swap_total 20
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 2847
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 2877
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 319479
telemt_user_connections_current{user="hello"} 628
telemt_user_octets_from_client{user="hello"} 6780296373 (6.31 GB)
telemt_user_octets_to_client{user="hello"} 74876947153 (69.73 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 21392.4 (5h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1247890
telemt_connections_bad_total 100494
telemt_connections_current 2561
telemt_connections_me_current 2561
telemt_handshake_timeouts_total 25533
telemt_upstream_connect_attempt_total 3529
telemt_upstream_connect_success_total 3528
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3529
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1603
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 17962
telemt_me_reconnect_success_total 2441
telemt_me_reader_eof_total 2492
telemt_me_idle_close_by_peer_total 2492
telemt_me_route_drop_no_conn_total 561921
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1041585
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4647
telemt_desync_full_logged_total 1543
telemt_desync_suppressed_total 3104
telemt_desync_frames_bucket_total{bucket="1_2"} 1068
telemt_desync_frames_bucket_total{bucket="3_10"} 1602
telemt_desync_frames_bucket_total{bucket="gt_10"} 1977
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 2424
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 2380
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 1040341
telemt_user_connections_current{user="hello"} 2561
telemt_user_octets_from_client{user="hello"} 20663281040 (19.24 GB)
telemt_user_octets_to_client{user="hello"} 600690774588 (559.44 GB)
telemt_user_unique_ips_current{user="hello"} 770
telemt_user_unique_ips_recent_window{user="hello"} 270
```