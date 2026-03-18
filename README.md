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

# Server Metrics 2026-03-18 12:59:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 15526.3 (4h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 568967
telemt_connections_bad_total 16700
telemt_handshake_timeouts_total 15648
telemt_upstream_connect_attempt_total 66066
telemt_upstream_connect_success_total 65112
telemt_upstream_connect_fail_total 954
telemt_upstream_connect_attempts_per_request{bucket="1"} 66066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60501
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4028
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 954
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 513971
telemt_me_reconnect_success_total 2323
telemt_me_reader_eof_total 2474
telemt_me_idle_close_by_peer_total 2472
telemt_me_route_drop_no_conn_total 340403
telemt_me_route_drop_channel_closed_total 112
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 437987
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1960
telemt_desync_full_logged_total 649
telemt_desync_suppressed_total 1311
telemt_desync_frames_bucket_total{bucket="1_2"} 548
telemt_desync_frames_bucket_total{bucket="3_10"} 689
telemt_desync_frames_bucket_total{bucket="gt_10"} 723
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2489
telemt_me_refill_failed_total 16672
telemt_me_writer_restored_same_endpoint_total 2218
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 496213
telemt_user_connections_current{user="hello"} 1826
telemt_user_octets_from_client{user="hello"} 6737545568 (6.27 GB)
telemt_user_octets_to_client{user="hello"} 126932003133 (118.21 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 598
telemt_user_unique_ips_recent_window{user="hello"} 268
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 15557.5 (4h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1544553
telemt_connections_bad_total 112351
telemt_handshake_timeouts_total 34775
telemt_upstream_connect_attempt_total 2795
telemt_upstream_connect_success_total 2783
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1287
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3055
telemt_me_reconnect_success_total 1914
telemt_me_reader_eof_total 1987
telemt_me_idle_close_by_peer_total 1986
telemt_me_route_drop_no_conn_total 1318999
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1323966
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4174
telemt_desync_full_logged_total 1274
telemt_desync_suppressed_total 2900
telemt_desync_frames_bucket_total{bucket="1_2"} 842
telemt_desync_frames_bucket_total{bucket="3_10"} 1690
telemt_desync_frames_bucket_total{bucket="gt_10"} 1642
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1958
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 1913
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 1322960
telemt_user_connections_current{user="hello"} 4181
telemt_user_octets_from_client{user="hello"} 33213652228 (30.93 GB)
telemt_user_octets_to_client{user="hello"} 393231594556 (366.23 GB)
telemt_user_unique_ips_current{user="hello"} 1263
telemt_user_unique_ips_recent_window{user="hello"} 587
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 15472.6 (4h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1096427
telemt_connections_bad_total 79069
telemt_handshake_timeouts_total 26542
telemt_upstream_connect_attempt_total 11197
telemt_upstream_connect_success_total 11197
telemt_upstream_connect_attempts_per_request{bucket="1"} 11197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8494
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2691
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 607835
telemt_me_reconnect_success_total 2138
telemt_me_reader_eof_total 2167
telemt_me_idle_close_by_peer_total 2166
telemt_me_route_drop_no_conn_total 462864
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 840908
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2506
telemt_desync_full_logged_total 847
telemt_desync_suppressed_total 1659
telemt_desync_frames_bucket_total{bucket="1_2"} 711
telemt_desync_frames_bucket_total{bucket="3_10"} 918
telemt_desync_frames_bucket_total{bucket="gt_10"} 877
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2151
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 2103
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 848405
telemt_user_connections_current{user="hello"} 3287
telemt_user_octets_from_client{user="hello"} 10713858183 (9.98 GB)
telemt_user_octets_to_client{user="hello"} 353190246036 (328.93 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 999
telemt_user_unique_ips_recent_window{user="hello"} 481
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 15502.5 (4h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1810691
telemt_connections_bad_total 27625
telemt_handshake_timeouts_total 168979
telemt_upstream_connect_attempt_total 12492
telemt_upstream_connect_success_total 12294
telemt_upstream_connect_fail_total 198
telemt_upstream_connect_attempts_per_request{bucket="1"} 12492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10947
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1308
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 198
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2830637
telemt_me_reconnect_success_total 1179
telemt_me_reader_eof_total 1745
telemt_me_idle_close_by_peer_total 1745
telemt_me_route_drop_no_conn_total 2740799
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1467870
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 8840
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_writer_pick_blocking_fallback_total 8840
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3125
telemt_desync_full_logged_total 957
telemt_desync_suppressed_total 2168
telemt_desync_frames_bucket_total{bucket="1_2"} 800
telemt_desync_frames_bucket_total{bucket="3_10"} 1311
telemt_desync_frames_bucket_total{bucket="gt_10"} 1014
telemt_me_writer_removed_unexpected_total 1792
telemt_me_refill_failed_total 100158
telemt_me_writer_restored_same_endpoint_total 1084
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 613
telemt_user_connections_total{user="hello"} 1486441
telemt_user_connections_current{user="hello"} 2933
telemt_user_octets_from_client{user="hello"} 23325565226 (21.72 GB)
telemt_user_octets_to_client{user="hello"} 225796116065 (210.29 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 901
telemt_user_unique_ips_recent_window{user="hello"} 525
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 15397.6 (4h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1152106
telemt_connections_bad_total 56378
telemt_handshake_timeouts_total 20143
telemt_upstream_connect_attempt_total 12208
telemt_upstream_connect_success_total 12207
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12208
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1535
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 227
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 2984997
telemt_me_reconnect_success_total 1880
telemt_me_reader_eof_total 1919
telemt_me_idle_close_by_peer_total 1919
telemt_me_route_drop_no_conn_total 960731
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 977323
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3183
telemt_desync_full_logged_total 1067
telemt_desync_suppressed_total 2116
telemt_desync_frames_bucket_total{bucket="1_2"} 462
telemt_desync_frames_bucket_total{bucket="3_10"} 1248
telemt_desync_frames_bucket_total{bucket="gt_10"} 1473
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1896
telemt_me_refill_failed_total 107189
telemt_me_writer_restored_same_endpoint_total 1765
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 977447
telemt_user_connections_current{user="hello"} 3467
telemt_user_octets_from_client{user="hello"} 15683671385 (14.61 GB)
telemt_user_octets_to_client{user="hello"} 369583495669 (344.20 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1090
telemt_user_unique_ips_recent_window{user="hello"} 506
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 15284.3 (4h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 329789
telemt_connections_bad_total 31445
telemt_handshake_timeouts_total 2501
telemt_upstream_connect_attempt_total 2867
telemt_upstream_connect_success_total 2867
telemt_upstream_connect_attempts_per_request{bucket="1"} 2867
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1316
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1543
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 7156
telemt_me_reconnect_success_total 2046
telemt_me_reader_eof_total 2241
telemt_me_idle_close_by_peer_total 2240
telemt_me_route_drop_no_conn_total 179073
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 281744
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 715
telemt_desync_full_logged_total 254
telemt_desync_suppressed_total 461
telemt_desync_frames_bucket_total{bucket="1_2"} 146
telemt_desync_frames_bucket_total{bucket="3_10"} 260
telemt_desync_frames_bucket_total{bucket="gt_10"} 309
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2223
telemt_me_refill_failed_total 159
telemt_me_writer_restored_same_endpoint_total 2038
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 177
telemt_user_connections_total{user="hello"} 272027
telemt_user_connections_current{user="hello"} 966
telemt_user_octets_from_client{user="hello"} 4495142276 (4.19 GB)
telemt_user_octets_to_client{user="hello"} 56969573044 (53.06 GB)
telemt_user_unique_ips_current{user="hello"} 335
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 15353.6 (4h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 935441
telemt_connections_bad_total 117280
telemt_handshake_timeouts_total 19971
telemt_upstream_connect_attempt_total 2743
telemt_upstream_connect_success_total 2716
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 2743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1506
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1202
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 1934
telemt_me_reconnect_success_total 1903
telemt_me_reader_eof_total 1954
telemt_me_idle_close_by_peer_total 1954
telemt_me_route_drop_no_conn_total 427395
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 727702
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2649
telemt_desync_full_logged_total 897
telemt_desync_suppressed_total 1752
telemt_desync_frames_bucket_total{bucket="1_2"} 471
telemt_desync_frames_bucket_total{bucket="3_10"} 917
telemt_desync_frames_bucket_total{bucket="gt_10"} 1261
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1917
telemt_me_writer_restored_same_endpoint_total 1893
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 727173
telemt_user_connections_current{user="hello"} 2962
telemt_user_octets_from_client{user="hello"} 15510608920 (14.45 GB)
telemt_user_octets_to_client{user="hello"} 355945170368 (331.50 GB)
telemt_user_unique_ips_current{user="hello"} 903
telemt_user_unique_ips_recent_window{user="hello"} 417
```