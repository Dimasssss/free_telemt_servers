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

# Server Metrics 2026-03-18 18:01:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 9393.9 (2h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 265532
telemt_connections_bad_total 16965
telemt_handshake_timeouts_total 6662
telemt_upstream_connect_attempt_total 1554
telemt_upstream_connect_success_total 1554
telemt_upstream_connect_attempts_per_request{bucket="1"} 1554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 768
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 760
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1053
telemt_me_reconnect_success_total 1049
telemt_me_reader_eof_total 1076
telemt_me_idle_close_by_peer_total 1076
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 121294
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 225861
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1204
telemt_desync_full_logged_total 373
telemt_desync_suppressed_total 831
telemt_desync_frames_bucket_total{bucket="1_2"} 274
telemt_desync_frames_bucket_total{bucket="3_10"} 388
telemt_desync_frames_bucket_total{bucket="gt_10"} 542
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1070
telemt_me_writer_restored_same_endpoint_total 1034
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 225759
telemt_user_connections_current{user="hello"} 1418
telemt_user_octets_from_client{user="hello"} 3236970804 (3.01 GB)
telemt_user_octets_to_client{user="hello"} 76683067260 (71.42 GB)
telemt_user_unique_ips_current{user="hello"} 491
telemt_user_unique_ips_recent_window{user="hello"} 200
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 14222.7 (3h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1430510
telemt_connections_bad_total 91000
telemt_connections_current 3696
telemt_connections_me_current 3696
telemt_handshake_timeouts_total 27324
telemt_upstream_connect_attempt_total 2430
telemt_upstream_connect_success_total 2417
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2430
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1299
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1099
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 1697
telemt_me_reconnect_success_total 1682
telemt_me_reader_eof_total 1656
telemt_me_idle_close_by_peer_total 1655
telemt_me_route_drop_no_conn_total 1475619
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1241355
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3772
telemt_desync_full_logged_total 1196
telemt_desync_suppressed_total 2576
telemt_desync_frames_bucket_total{bucket="1_2"} 675
telemt_desync_frames_bucket_total{bucket="3_10"} 1500
telemt_desync_frames_bucket_total{bucket="gt_10"} 1597
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1623
telemt_me_writer_restored_same_endpoint_total 1680
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1236648
telemt_user_connections_current{user="hello"} 3696
telemt_user_octets_from_client{user="hello"} 16195390296 (15.08 GB)
telemt_user_octets_to_client{user="hello"} 365142423596 (340.07 GB)
telemt_user_unique_ips_current{user="hello"} 1187
telemt_user_unique_ips_recent_window{user="hello"} 516
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 14150.8 (3h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1007238
telemt_connections_bad_total 81914
telemt_connections_current 3307
telemt_connections_me_current 3307
telemt_handshake_timeouts_total 22001
telemt_upstream_connect_attempt_total 1983
telemt_upstream_connect_success_total 1972
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1983
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 924
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1251
telemt_me_reconnect_success_total 1238
telemt_me_reader_eof_total 1311
telemt_me_idle_close_by_peer_total 1311
telemt_me_route_drop_no_conn_total 447994
telemt_me_route_drop_channel_closed_total 41
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 830549
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3596
telemt_desync_full_logged_total 1098
telemt_desync_suppressed_total 2498
telemt_desync_frames_bucket_total{bucket="1_2"} 895
telemt_desync_frames_bucket_total{bucket="3_10"} 1348
telemt_desync_frames_bucket_total{bucket="gt_10"} 1353
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 1275
telemt_me_writer_restored_same_endpoint_total 1221
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 830184
telemt_user_connections_current{user="hello"} 3307
telemt_user_octets_from_client{user="hello"} 19778057716 (18.42 GB)
telemt_user_octets_to_client{user="hello"} 360113875628 (335.38 GB)
telemt_user_unique_ips_current{user="hello"} 1037
telemt_user_unique_ips_recent_window{user="hello"} 459
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 14865.0 (4h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1491023
telemt_connections_bad_total 34657
telemt_connections_current 3091
telemt_connections_me_current 3091
telemt_handshake_timeouts_total 16683
telemt_upstream_connect_attempt_total 2287
telemt_upstream_connect_success_total 2271
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 2287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1065
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1503
telemt_me_reconnect_success_total 1483
telemt_me_reader_eof_total 1519
telemt_me_idle_close_by_peer_total 1518
telemt_me_route_drop_no_conn_total 2502627
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1333071
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5129
telemt_desync_full_logged_total 1269
telemt_desync_suppressed_total 3860
telemt_desync_frames_bucket_total{bucket="1_2"} 1162
telemt_desync_frames_bucket_total{bucket="3_10"} 2405
telemt_desync_frames_bucket_total{bucket="gt_10"} 1562
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1483
telemt_me_writer_restored_same_endpoint_total 1472
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 1332990
telemt_user_connections_current{user="hello"} 3091
telemt_user_octets_from_client{user="hello"} 12868238696 (11.98 GB)
telemt_user_octets_to_client{user="hello"} 221617430904 (206.40 GB)
telemt_user_unique_ips_current{user="hello"} 921
telemt_user_unique_ips_recent_window{user="hello"} 538
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 9380.1 (2h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 703674
telemt_connections_bad_total 129295
telemt_handshake_timeouts_total 6973
telemt_upstream_connect_attempt_total 1703
telemt_upstream_connect_success_total 1649
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 1703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 852
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 775
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 3230
telemt_me_reconnect_success_total 1140
telemt_me_reader_eof_total 1219
telemt_me_idle_close_by_peer_total 1219
telemt_me_route_drop_no_conn_total 281149
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 513502
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1888
telemt_desync_full_logged_total 644
telemt_desync_suppressed_total 1244
telemt_desync_frames_bucket_total{bucket="1_2"} 351
telemt_desync_frames_bucket_total{bucket="3_10"} 642
telemt_desync_frames_bucket_total{bucket="gt_10"} 895
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1220
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1114
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 513002
telemt_user_connections_current{user="hello"} 3337
telemt_user_octets_from_client{user="hello"} 8205908184 (7.64 GB)
telemt_user_octets_to_client{user="hello"} 218866123276 (203.83 GB)
telemt_user_unique_ips_current{user="hello"} 1067
telemt_user_unique_ips_recent_window{user="hello"} 456
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 14316.8 (3h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 259962
telemt_connections_bad_total 10055
telemt_connections_current 896
telemt_connections_me_current 896
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 2797
telemt_upstream_connect_attempt_total 6542
telemt_upstream_connect_success_total 6527
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 6542
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3002
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 45
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_reconnect_attempts_total 331433
telemt_me_reconnect_success_total 1967
telemt_me_reader_eof_total 1955
telemt_me_idle_close_by_peer_total 1955
telemt_me_route_drop_no_conn_total 167510
telemt_me_route_drop_channel_closed_total 69
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 230193
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 444
telemt_desync_full_logged_total 164
telemt_desync_suppressed_total 280
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 181
telemt_desync_frames_bucket_total{bucket="gt_10"} 178
telemt_pool_swap_total 11
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 1910
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 1956
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 233910
telemt_user_connections_current{user="hello"} 896
telemt_user_octets_from_client{user="hello"} 3430000489 (3.19 GB)
telemt_user_octets_to_client{user="hello"} 47699470725 (44.42 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 13384.4 (3h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 802601
telemt_connections_bad_total 55346
telemt_connections_current 2860
telemt_connections_me_current 2860
telemt_handshake_timeouts_total 14653
telemt_upstream_connect_attempt_total 2302
telemt_upstream_connect_success_total 2301
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1033
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 17123
telemt_me_reconnect_success_total 1608
telemt_me_reader_eof_total 1598
telemt_me_idle_close_by_peer_total 1598
telemt_me_route_drop_no_conn_total 424872
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 675246
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2673
telemt_desync_full_logged_total 921
telemt_desync_suppressed_total 1752
telemt_desync_frames_bucket_total{bucket="1_2"} 652
telemt_desync_frames_bucket_total{bucket="3_10"} 955
telemt_desync_frames_bucket_total{bucket="gt_10"} 1066
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1573
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1547
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 674271
telemt_user_connections_current{user="hello"} 2860
telemt_user_octets_from_client{user="hello"} 13020742812 (12.13 GB)
telemt_user_octets_to_client{user="hello"} 340350440568 (316.98 GB)
telemt_user_unique_ips_current{user="hello"} 898
telemt_user_unique_ips_recent_window{user="hello"} 379
```