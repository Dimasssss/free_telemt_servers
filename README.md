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

# Server Metrics 2026-03-18 12:18:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 13071.2 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 470442
telemt_connections_bad_total 6286
telemt_handshake_timeouts_total 13055
telemt_upstream_connect_attempt_total 65605
telemt_upstream_connect_success_total 64664
telemt_upstream_connect_fail_total 941
telemt_upstream_connect_attempts_per_request{bucket="1"} 65605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3799
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 941
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 509818
telemt_me_reconnect_success_total 2014
telemt_me_reader_eof_total 2043
telemt_me_idle_close_by_peer_total 2041
telemt_me_route_drop_no_conn_total 279821
telemt_me_route_drop_channel_closed_total 89
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 356805
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1475
telemt_desync_full_logged_total 479
telemt_desync_suppressed_total 996
telemt_desync_frames_bucket_total{bucket="1_2"} 427
telemt_desync_frames_bucket_total{bucket="3_10"} 530
telemt_desync_frames_bucket_total{bucket="gt_10"} 518
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2055
telemt_me_refill_failed_total 16552
telemt_me_writer_restored_same_endpoint_total 1909
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 415084
telemt_user_connections_current{user="hello"} 1655
telemt_user_octets_from_client{user="hello"} 5707598260 (5.32 GB)
telemt_user_octets_to_client{user="hello"} 110062023437 (102.50 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 544
telemt_user_unique_ips_recent_window{user="hello"} 259
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 13103.2 (3h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1316391
telemt_connections_bad_total 93255
telemt_handshake_timeouts_total 30415
telemt_upstream_connect_attempt_total 2270
telemt_upstream_connect_success_total 2258
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2270
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1017
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 1577
telemt_me_reconnect_success_total 1533
telemt_me_reader_eof_total 1555
telemt_me_idle_close_by_peer_total 1554
telemt_me_route_drop_no_conn_total 1171864
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1134557
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3575
telemt_desync_full_logged_total 1049
telemt_desync_suppressed_total 2526
telemt_desync_frames_bucket_total{bucket="1_2"} 706
telemt_desync_frames_bucket_total{bucket="3_10"} 1451
telemt_desync_frames_bucket_total{bucket="gt_10"} 1418
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1537
telemt_me_writer_restored_same_endpoint_total 1532
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 1133657
telemt_user_connections_current{user="hello"} 4283
telemt_user_octets_from_client{user="hello"} 28656522904 (26.69 GB)
telemt_user_octets_to_client{user="hello"} 328438068020 (305.88 GB)
telemt_user_unique_ips_current{user="hello"} 1230
telemt_user_unique_ips_recent_window{user="hello"} 591
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 13047.7 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1445621
telemt_connections_bad_total 22232
telemt_handshake_timeouts_total 160442
telemt_upstream_connect_attempt_total 12330
telemt_upstream_connect_success_total 12153
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 12330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1256
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2827084
telemt_me_reconnect_success_total 1178
telemt_me_reader_eof_total 1636
telemt_me_idle_close_by_peer_total 1636
telemt_me_route_drop_no_conn_total 2057831
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1137245
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 8840
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_writer_pick_blocking_fallback_total 8840
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2399
telemt_desync_full_logged_total 779
telemt_desync_suppressed_total 1620
telemt_desync_frames_bucket_total{bucket="1_2"} 587
telemt_desync_frames_bucket_total{bucket="3_10"} 966
telemt_desync_frames_bucket_total{bucket="gt_10"} 846
telemt_me_writer_removed_unexpected_total 1680
telemt_me_refill_failed_total 100047
telemt_me_writer_restored_same_endpoint_total 1083
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 502
telemt_user_connections_total{user="hello"} 1155902
telemt_user_connections_current{user="hello"} 3443
telemt_user_octets_from_client{user="hello"} 10260511882 (9.56 GB)
telemt_user_octets_to_client{user="hello"} 199702225649 (185.99 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 954
telemt_user_unique_ips_recent_window{user="hello"} 569
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 12942.7 (3h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 962304
telemt_connections_bad_total 40506
telemt_handshake_timeouts_total 16752
telemt_upstream_connect_attempt_total 11721
telemt_upstream_connect_success_total 11720
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11721
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1346
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2983482
telemt_me_reconnect_success_total 1518
telemt_me_reader_eof_total 1515
telemt_me_idle_close_by_peer_total 1515
telemt_me_route_drop_no_conn_total 602664
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 820010
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2804
telemt_desync_full_logged_total 927
telemt_desync_suppressed_total 1877
telemt_desync_frames_bucket_total{bucket="1_2"} 408
telemt_desync_frames_bucket_total{bucket="3_10"} 1105
telemt_desync_frames_bucket_total{bucket="gt_10"} 1291
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1492
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 1403
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 820244
telemt_user_connections_current{user="hello"} 3360
telemt_user_octets_from_client{user="hello"} 12250497269 (11.41 GB)
telemt_user_octets_to_client{user="hello"} 315277649469 (293.63 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1059
telemt_user_unique_ips_recent_window{user="hello"} 494
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 12828.0 (3h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 270837
telemt_connections_bad_total 24439
telemt_handshake_timeouts_total 2084
telemt_upstream_connect_attempt_total 2590
telemt_upstream_connect_success_total 2590
telemt_upstream_connect_attempts_per_request{bucket="1"} 2590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1354
telemt_me_reconnect_attempts_total 4314
telemt_me_reconnect_success_total 1866
telemt_me_reader_eof_total 1980
telemt_me_idle_close_by_peer_total 1979
telemt_me_route_drop_no_conn_total 135448
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 233751
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 595
telemt_desync_full_logged_total 211
telemt_desync_suppressed_total 384
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 210
telemt_desync_frames_bucket_total{bucket="gt_10"} 261
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1957
telemt_me_refill_failed_total 76
telemt_me_writer_restored_same_endpoint_total 1858
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 224051
telemt_user_connections_current{user="hello"} 998
telemt_user_octets_from_client{user="hello"} 4143011156 (3.86 GB)
telemt_user_octets_to_client{user="hello"} 50912434700 (47.42 GB)
telemt_user_unique_ips_current{user="hello"} 338
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 12898.7 (3h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 775203
telemt_connections_bad_total 105574
telemt_handshake_timeouts_total 16816
telemt_upstream_connect_attempt_total 2347
telemt_upstream_connect_success_total 2323
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 2347
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1025
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 1632
telemt_me_reconnect_success_total 1605
telemt_me_reader_eof_total 1641
telemt_me_idle_close_by_peer_total 1641
telemt_me_route_drop_no_conn_total 304061
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 591700
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2181
telemt_desync_full_logged_total 743
telemt_desync_suppressed_total 1438
telemt_desync_frames_bucket_total{bucket="1_2"} 368
telemt_desync_frames_bucket_total{bucket="3_10"} 768
telemt_desync_frames_bucket_total{bucket="gt_10"} 1045
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1611
telemt_me_writer_restored_same_endpoint_total 1595
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 591236
telemt_user_connections_current{user="hello"} 3056
telemt_user_octets_from_client{user="hello"} 12562269120 (11.70 GB)
telemt_user_octets_to_client{user="hello"} 302761313932 (281.97 GB)
telemt_user_unique_ips_current{user="hello"} 922
telemt_user_unique_ips_recent_window{user="hello"} 416
```