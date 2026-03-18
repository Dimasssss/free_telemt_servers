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

# Server Metrics 2026-03-18 17:26:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 7244.1 (2h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 217145
telemt_connections_bad_total 14576
telemt_handshake_timeouts_total 5776
telemt_upstream_connect_attempt_total 1152
telemt_upstream_connect_success_total 1152
telemt_upstream_connect_attempts_per_request{bucket="1"} 1152
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 578
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 548
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 762
telemt_me_reconnect_success_total 760
telemt_me_reader_eof_total 778
telemt_me_idle_close_by_peer_total 778
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 103333
telemt_me_route_drop_channel_closed_total 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 182430
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1017
telemt_desync_full_logged_total 309
telemt_desync_suppressed_total 708
telemt_desync_frames_bucket_total{bucket="1_2"} 245
telemt_desync_frames_bucket_total{bucket="3_10"} 336
telemt_desync_frames_bucket_total{bucket="gt_10"} 436
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 780
telemt_me_writer_restored_same_endpoint_total 747
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 182344
telemt_user_connections_current{user="hello"} 1388
telemt_user_octets_from_client{user="hello"} 2583407780 (2.41 GB)
telemt_user_octets_to_client{user="hello"} 61357438248 (57.14 GB)
telemt_user_unique_ips_current{user="hello"} 485
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 12072.6 (3h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1188658
telemt_connections_bad_total 76229
telemt_connections_current 3727
telemt_connections_me_current 3727
telemt_handshake_timeouts_total 17184
telemt_upstream_connect_attempt_total 2156
telemt_upstream_connect_success_total 2145
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 969
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 1511
telemt_me_reconnect_success_total 1499
telemt_me_reader_eof_total 1462
telemt_me_idle_close_by_peer_total 1461
telemt_me_route_drop_no_conn_total 1078951
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1037733
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3078
telemt_desync_full_logged_total 999
telemt_desync_suppressed_total 2079
telemt_desync_frames_bucket_total{bucket="1_2"} 590
telemt_desync_frames_bucket_total{bucket="3_10"} 1217
telemt_desync_frames_bucket_total{bucket="gt_10"} 1271
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1433
telemt_me_writer_restored_same_endpoint_total 1497
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1036870
telemt_user_connections_current{user="hello"} 3727
telemt_user_octets_from_client{user="hello"} 14009115072 (13.05 GB)
telemt_user_octets_to_client{user="hello"} 316080661096 (294.37 GB)
telemt_user_unique_ips_current{user="hello"} 1173
telemt_user_unique_ips_recent_window{user="hello"} 478
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 12000.9 (3h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 852275
telemt_connections_bad_total 65219
telemt_connections_current 3167
telemt_connections_me_current 3167
telemt_handshake_timeouts_total 18821
telemt_upstream_connect_attempt_total 1703
telemt_upstream_connect_success_total 1695
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 893
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 789
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1059
telemt_me_reconnect_success_total 1049
telemt_me_reader_eof_total 1109
telemt_me_idle_close_by_peer_total 1109
telemt_me_route_drop_no_conn_total 398593
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 709796
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2880
telemt_desync_full_logged_total 880
telemt_desync_suppressed_total 2000
telemt_desync_frames_bucket_total{bucket="1_2"} 684
telemt_desync_frames_bucket_total{bucket="3_10"} 1081
telemt_desync_frames_bucket_total{bucket="gt_10"} 1115
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1083
telemt_me_writer_restored_same_endpoint_total 1032
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 709438
telemt_user_connections_current{user="hello"} 3167
telemt_user_octets_from_client{user="hello"} 13609383776 (12.67 GB)
telemt_user_octets_to_client{user="hello"} 301151219716 (280.47 GB)
telemt_user_unique_ips_current{user="hello"} 1010
telemt_user_unique_ips_recent_window{user="hello"} 406
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 12715.5 (3h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1258174
telemt_connections_bad_total 26676
telemt_connections_current 2793
telemt_connections_me_current 2793
telemt_handshake_timeouts_total 14984
telemt_upstream_connect_attempt_total 1995
telemt_upstream_connect_success_total 1981
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 1995
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1020
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 942
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1299
telemt_me_reconnect_success_total 1282
telemt_me_reader_eof_total 1303
telemt_me_idle_close_by_peer_total 1302
telemt_me_route_drop_no_conn_total 2136752
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1128941
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4106
telemt_desync_full_logged_total 1058
telemt_desync_suppressed_total 3048
telemt_desync_frames_bucket_total{bucket="1_2"} 949
telemt_desync_frames_bucket_total{bucket="3_10"} 1868
telemt_desync_frames_bucket_total{bucket="gt_10"} 1289
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1277
telemt_me_writer_restored_same_endpoint_total 1271
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 1128870
telemt_user_connections_current{user="hello"} 2793
telemt_user_octets_from_client{user="hello"} 9601096192 (8.94 GB)
telemt_user_octets_to_client{user="hello"} 191523867124 (178.37 GB)
telemt_user_unique_ips_current{user="hello"} 852
telemt_user_unique_ips_recent_window{user="hello"} 408
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 7230.1 (2h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 544904
telemt_connections_bad_total 95252
telemt_handshake_timeouts_total 5269
telemt_upstream_connect_attempt_total 1244
telemt_upstream_connect_success_total 1208
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 1244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 639
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 559
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 1829
telemt_me_reconnect_success_total 829
telemt_me_reader_eof_total 859
telemt_me_idle_close_by_peer_total 859
telemt_me_route_drop_no_conn_total 226127
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 402942
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1550
telemt_desync_full_logged_total 521
telemt_desync_suppressed_total 1029
telemt_desync_frames_bucket_total{bucket="1_2"} 278
telemt_desync_frames_bucket_total{bucket="3_10"} 505
telemt_desync_frames_bucket_total{bucket="gt_10"} 767
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 869
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 803
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 402474
telemt_user_connections_current{user="hello"} 3046
telemt_user_octets_from_client{user="hello"} 6461850676 (6.02 GB)
telemt_user_octets_to_client{user="hello"} 169213850760 (157.59 GB)
telemt_user_unique_ips_current{user="hello"} 1051
telemt_user_unique_ips_recent_window{user="hello"} 400
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 12164.7 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218052
telemt_connections_bad_total 7735
telemt_connections_current 829
telemt_connections_me_current 829
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 2405
telemt_upstream_connect_attempt_total 6262
telemt_upstream_connect_success_total 6249
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 6262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2839
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 331241
telemt_me_reconnect_success_total 1776
telemt_me_reader_eof_total 1753
telemt_me_idle_close_by_peer_total 1753
telemt_me_route_drop_no_conn_total 120893
telemt_me_route_drop_channel_closed_total 53
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 193678
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 403
telemt_desync_full_logged_total 144
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 166
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1714
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 1765
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 197399
telemt_user_connections_current{user="hello"} 829
telemt_user_octets_from_client{user="hello"} 2839845881 (2.64 GB)
telemt_user_octets_to_client{user="hello"} 41838481381 (38.97 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 11234.6 (3h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 688821
telemt_connections_bad_total 48140
telemt_connections_current 2946
telemt_connections_me_current 2946
telemt_handshake_timeouts_total 13305
telemt_upstream_connect_attempt_total 2013
telemt_upstream_connect_success_total 2012
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2013
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1110
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 893
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 16921
telemt_me_reconnect_success_total 1407
telemt_me_reader_eof_total 1385
telemt_me_idle_close_by_peer_total 1385
telemt_me_route_drop_no_conn_total 391942
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 576527
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2185
telemt_desync_full_logged_total 752
telemt_desync_suppressed_total 1433
telemt_desync_frames_bucket_total{bucket="1_2"} 529
telemt_desync_frames_bucket_total{bucket="3_10"} 781
telemt_desync_frames_bucket_total{bucket="gt_10"} 875
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1368
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1346
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 575561
telemt_user_connections_current{user="hello"} 2946
telemt_user_octets_from_client{user="hello"} 10836844288 (10.09 GB)
telemt_user_octets_to_client{user="hello"} 280082340188 (260.85 GB)
telemt_user_unique_ips_current{user="hello"} 902
telemt_user_unique_ips_recent_window{user="hello"} 349
```