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

# Server Metrics 2026-03-18 18:22:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 10626.3 (2h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 294066
telemt_connections_bad_total 18085
telemt_handshake_timeouts_total 7166
telemt_upstream_connect_attempt_total 1741
telemt_upstream_connect_success_total 1741
telemt_upstream_connect_attempts_per_request{bucket="1"} 1741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 851
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 1197
telemt_me_reconnect_success_total 1192
telemt_me_reader_eof_total 1233
telemt_me_idle_close_by_peer_total 1233
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 132888
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 251660
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1407
telemt_desync_full_logged_total 411
telemt_desync_suppressed_total 996
telemt_desync_frames_bucket_total{bucket="1_2"} 347
telemt_desync_frames_bucket_total{bucket="3_10"} 444
telemt_desync_frames_bucket_total{bucket="gt_10"} 616
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1217
telemt_me_writer_restored_same_endpoint_total 1177
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 251554
telemt_user_connections_current{user="hello"} 1290
telemt_user_octets_from_client{user="hello"} 3518580956 (3.28 GB)
telemt_user_octets_to_client{user="hello"} 85193597648 (79.34 GB)
telemt_user_unique_ips_current{user="hello"} 430
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 15454.0 (4h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1532080
telemt_connections_bad_total 102624
telemt_connections_current 3837
telemt_connections_me_current 3837
telemt_handshake_timeouts_total 28943
telemt_upstream_connect_attempt_total 2606
telemt_upstream_connect_success_total 2593
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2606
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1382
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1190
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 1787
telemt_me_reconnect_success_total 1772
telemt_me_reader_eof_total 1753
telemt_me_idle_close_by_peer_total 1752
telemt_me_route_drop_no_conn_total 1514530
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1325483
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4191
telemt_desync_full_logged_total 1330
telemt_desync_suppressed_total 2861
telemt_desync_frames_bucket_total{bucket="1_2"} 730
telemt_desync_frames_bucket_total{bucket="3_10"} 1637
telemt_desync_frames_bucket_total{bucket="gt_10"} 1824
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1715
telemt_me_writer_restored_same_endpoint_total 1770
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1320846
telemt_user_connections_current{user="hello"} 3837
telemt_user_octets_from_client{user="hello"} 17321348564 (16.13 GB)
telemt_user_octets_to_client{user="hello"} 401713527468 (374.12 GB)
telemt_user_unique_ips_current{user="hello"} 1218
telemt_user_unique_ips_recent_window{user="hello"} 480
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 15382.0 (4h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1110827
telemt_connections_bad_total 90807
telemt_connections_current 3686
telemt_connections_me_current 3686
telemt_handshake_timeouts_total 23639
telemt_upstream_connect_attempt_total 2156
telemt_upstream_connect_success_total 2145
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1125
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1007
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1345
telemt_me_reconnect_success_total 1331
telemt_me_reader_eof_total 1411
telemt_me_idle_close_by_peer_total 1411
telemt_me_route_drop_no_conn_total 478997
telemt_me_route_drop_channel_closed_total 42
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 905032
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4194
telemt_desync_full_logged_total 1290
telemt_desync_suppressed_total 2904
telemt_desync_frames_bucket_total{bucket="1_2"} 1053
telemt_desync_frames_bucket_total{bucket="3_10"} 1574
telemt_desync_frames_bucket_total{bucket="gt_10"} 1567
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 1370
telemt_me_writer_restored_same_endpoint_total 1314
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 904651
telemt_user_connections_current{user="hello"} 3686
telemt_user_octets_from_client{user="hello"} 21015774276 (19.57 GB)
telemt_user_octets_to_client{user="hello"} 400039062500 (372.57 GB)
telemt_user_unique_ips_current{user="hello"} 1123
telemt_user_unique_ips_recent_window{user="hello"} 462
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 16096.8 (4h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1635803
telemt_connections_bad_total 37369
telemt_connections_current 2953
telemt_connections_me_current 2953
telemt_handshake_timeouts_total 18203
telemt_upstream_connect_attempt_total 2415
telemt_upstream_connect_success_total 2397
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 2415
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1123
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1586
telemt_me_reconnect_success_total 1565
telemt_me_reader_eof_total 1609
telemt_me_idle_close_by_peer_total 1608
telemt_me_route_drop_no_conn_total 2747104
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1463946
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5645
telemt_desync_full_logged_total 1395
telemt_desync_suppressed_total 4250
telemt_desync_frames_bucket_total{bucket="1_2"} 1269
telemt_desync_frames_bucket_total{bucket="3_10"} 2648
telemt_desync_frames_bucket_total{bucket="gt_10"} 1728
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 1570
telemt_me_writer_restored_same_endpoint_total 1554
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 1463888
telemt_user_connections_current{user="hello"} 2953
telemt_user_octets_from_client{user="hello"} 13783481444 (12.84 GB)
telemt_user_octets_to_client{user="hello"} 239253263444 (222.82 GB)
telemt_user_unique_ips_current{user="hello"} 921
telemt_user_unique_ips_recent_window{user="hello"} 410
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 10612.0 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 801859
telemt_connections_bad_total 144976
telemt_handshake_timeouts_total 7777
telemt_upstream_connect_attempt_total 1844
telemt_upstream_connect_success_total 1786
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 1844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 840
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 3324
telemt_me_reconnect_success_total 1233
telemt_me_reader_eof_total 1320
telemt_me_idle_close_by_peer_total 1320
telemt_me_route_drop_no_conn_total 339991
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 586578
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2081
telemt_desync_full_logged_total 726
telemt_desync_suppressed_total 1355
telemt_desync_frames_bucket_total{bucket="1_2"} 389
telemt_desync_frames_bucket_total{bucket="3_10"} 696
telemt_desync_frames_bucket_total{bucket="gt_10"} 996
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1316
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1207
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 586108
telemt_user_connections_current{user="hello"} 3677
telemt_user_octets_from_client{user="hello"} 9731427652 (9.06 GB)
telemt_user_octets_to_client{user="hello"} 251495656020 (234.22 GB)
telemt_user_unique_ips_current{user="hello"} 1141
telemt_user_unique_ips_recent_window{user="hello"} 445
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 15545.9 (4h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 277438
telemt_connections_bad_total 10083
telemt_connections_current 742
telemt_connections_me_current 742
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 2929
telemt_upstream_connect_attempt_total 6771
telemt_upstream_connect_success_total 6754
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 6771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3536
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3148
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 50
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 331574
telemt_me_reconnect_success_total 2107
telemt_me_reader_eof_total 2113
telemt_me_idle_close_by_peer_total 2113
telemt_me_route_drop_no_conn_total 180725
telemt_me_route_drop_channel_closed_total 81
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 246279
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 482
telemt_desync_full_logged_total 178
telemt_desync_suppressed_total 304
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 198
telemt_desync_frames_bucket_total{bucket="gt_10"} 192
telemt_pool_swap_total 13
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 2056
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 2096
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 249973
telemt_user_connections_current{user="hello"} 742
telemt_user_octets_from_client{user="hello"} 3587888613 (3.34 GB)
telemt_user_octets_to_client{user="hello"} 51903445213 (48.34 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 269
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 14616.3 (4h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 868466
telemt_connections_bad_total 57562
telemt_connections_current 3152
telemt_connections_me_current 3152
telemt_handshake_timeouts_total 15410
telemt_upstream_connect_attempt_total 2526
telemt_upstream_connect_success_total 2525
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2526
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1135
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 17260
telemt_me_reconnect_success_total 1745
telemt_me_reader_eof_total 1746
telemt_me_idle_close_by_peer_total 1746
telemt_me_route_drop_no_conn_total 449385
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 734842
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2996
telemt_desync_full_logged_total 1028
telemt_desync_suppressed_total 1968
telemt_desync_frames_bucket_total{bucket="1_2"} 699
telemt_desync_frames_bucket_total{bucket="3_10"} 1079
telemt_desync_frames_bucket_total{bucket="gt_10"} 1218
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1712
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1684
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 733798
telemt_user_connections_current{user="hello"} 3152
telemt_user_octets_from_client{user="hello"} 14556243480 (13.56 GB)
telemt_user_octets_to_client{user="hello"} 386592818500 (360.04 GB)
telemt_user_unique_ips_current{user="hello"} 908
telemt_user_unique_ips_recent_window{user="hello"} 361
```