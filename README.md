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

# Server Metrics 2026-03-18 18:32:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 11239.9 (3h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 307930
telemt_connections_bad_total 18731
telemt_handshake_timeouts_total 7302
telemt_upstream_connect_attempt_total 1865
telemt_upstream_connect_success_total 1865
telemt_upstream_connect_attempts_per_request{bucket="1"} 1865
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 928
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 911
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 1277
telemt_me_reconnect_success_total 1272
telemt_me_reader_eof_total 1318
telemt_me_idle_close_by_peer_total 1318
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 137277
telemt_me_route_drop_channel_closed_total 56
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 264015
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1508
telemt_desync_full_logged_total 436
telemt_desync_suppressed_total 1072
telemt_desync_frames_bucket_total{bucket="1_2"} 375
telemt_desync_frames_bucket_total{bucket="3_10"} 470
telemt_desync_frames_bucket_total{bucket="gt_10"} 663
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1297
telemt_me_writer_restored_same_endpoint_total 1257
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 263902
telemt_user_connections_current{user="hello"} 1278
telemt_user_octets_from_client{user="hello"} 3671032708 (3.42 GB)
telemt_user_octets_to_client{user="hello"} 89214079096 (83.09 GB)
telemt_user_unique_ips_current{user="hello"} 461
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 16068.3 (4h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1581387
telemt_connections_bad_total 106056
telemt_connections_current 3773
telemt_connections_me_current 3773
telemt_handshake_timeouts_total 29907
telemt_upstream_connect_attempt_total 2655
telemt_upstream_connect_success_total 2642
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1215
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 1836
telemt_me_reconnect_success_total 1821
telemt_me_reader_eof_total 1807
telemt_me_idle_close_by_peer_total 1806
telemt_me_route_drop_no_conn_total 1539979
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1367832
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4370
telemt_desync_full_logged_total 1382
telemt_desync_suppressed_total 2988
telemt_desync_frames_bucket_total{bucket="1_2"} 767
telemt_desync_frames_bucket_total{bucket="3_10"} 1717
telemt_desync_frames_bucket_total{bucket="gt_10"} 1886
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1766
telemt_me_writer_restored_same_endpoint_total 1819
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1362980
telemt_user_connections_current{user="hello"} 3773
telemt_user_octets_from_client{user="hello"} 18120076456 (16.88 GB)
telemt_user_octets_to_client{user="hello"} 419015067740 (390.24 GB)
telemt_user_unique_ips_current{user="hello"} 1171
telemt_user_unique_ips_recent_window{user="hello"} 468
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 16710.7 (4h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1722161
telemt_connections_bad_total 38214
telemt_connections_current 3023
telemt_connections_me_current 3023
telemt_handshake_timeouts_total 18663
telemt_upstream_connect_attempt_total 2519
telemt_upstream_connect_success_total 2500
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 2519
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1173
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1646
telemt_me_reconnect_success_total 1624
telemt_me_reader_eof_total 1672
telemt_me_idle_close_by_peer_total 1671
telemt_me_route_drop_no_conn_total 2917022
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1542954
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5862
telemt_desync_full_logged_total 1454
telemt_desync_suppressed_total 4408
telemt_desync_frames_bucket_total{bucket="1_2"} 1328
telemt_desync_frames_bucket_total{bucket="3_10"} 2749
telemt_desync_frames_bucket_total{bucket="gt_10"} 1785
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 1629
telemt_me_writer_restored_same_endpoint_total 1613
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 1542894
telemt_user_connections_current{user="hello"} 3023
telemt_user_octets_from_client{user="hello"} 14165980048 (13.19 GB)
telemt_user_octets_to_client{user="hello"} 247905830432 (230.88 GB)
telemt_user_unique_ips_current{user="hello"} 924
telemt_user_unique_ips_recent_window{user="hello"} 545
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 11225.6 (3h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 845951
telemt_connections_bad_total 152654
telemt_handshake_timeouts_total 8074
telemt_upstream_connect_attempt_total 1979
telemt_upstream_connect_success_total 1913
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 1979
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 895
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 3408
telemt_me_reconnect_success_total 1316
telemt_me_reader_eof_total 1405
telemt_me_idle_close_by_peer_total 1405
telemt_me_route_drop_no_conn_total 357958
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 619423
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2179
telemt_desync_full_logged_total 758
telemt_desync_suppressed_total 1421
telemt_desync_frames_bucket_total{bucket="1_2"} 409
telemt_desync_frames_bucket_total{bucket="3_10"} 735
telemt_desync_frames_bucket_total{bucket="gt_10"} 1035
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1401
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1290
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 618927
telemt_user_connections_current{user="hello"} 3694
telemt_user_octets_from_client{user="hello"} 10603442256 (9.88 GB)
telemt_user_octets_to_client{user="hello"} 268319709360 (249.89 GB)
telemt_user_unique_ips_current{user="hello"} 1146
telemt_user_unique_ips_recent_window{user="hello"} 451
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 16159.8 (4h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 284980
telemt_connections_bad_total 10401
telemt_connections_current 743
telemt_connections_me_current 743
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 2974
telemt_upstream_connect_attempt_total 6833
telemt_upstream_connect_success_total 6816
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 6833
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3203
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 50
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 331636
telemt_me_reconnect_success_total 2168
telemt_me_reader_eof_total 2175
telemt_me_idle_close_by_peer_total 2175
telemt_me_route_drop_no_conn_total 183593
telemt_me_route_drop_channel_closed_total 88
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 252999
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 501
telemt_desync_full_logged_total 185
telemt_desync_suppressed_total 316
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 204
telemt_desync_frames_bucket_total{bucket="gt_10"} 198
telemt_pool_swap_total 13
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 2118
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 2157
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 256690
telemt_user_connections_current{user="hello"} 743
telemt_user_octets_from_client{user="hello"} 3634928569 (3.39 GB)
telemt_user_octets_to_client{user="hello"} 53838227477 (50.14 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 248
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 15229.8 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 901830
telemt_connections_bad_total 57941
telemt_connections_current 3329
telemt_connections_me_current 3329
telemt_handshake_timeouts_total 16292
telemt_upstream_connect_attempt_total 2574
telemt_upstream_connect_success_total 2573
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2574
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1396
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1160
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 17308
telemt_me_reconnect_success_total 1793
telemt_me_reader_eof_total 1795
telemt_me_idle_close_by_peer_total 1795
telemt_me_route_drop_no_conn_total 460056
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 765640
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3134
telemt_desync_full_logged_total 1073
telemt_desync_suppressed_total 2061
telemt_desync_frames_bucket_total{bucket="1_2"} 729
telemt_desync_frames_bucket_total{bucket="3_10"} 1124
telemt_desync_frames_bucket_total{bucket="gt_10"} 1281
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1761
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1732
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 764589
telemt_user_connections_current{user="hello"} 3329
telemt_user_octets_from_client{user="hello"} 15472772260 (14.41 GB)
telemt_user_octets_to_client{user="hello"} 407236389244 (379.27 GB)
telemt_user_unique_ips_current{user="hello"} 941
telemt_user_unique_ips_recent_window{user="hello"} 395
```