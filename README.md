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

# Server Metrics 2026-03-17 17:02:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 80226.4 (22h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 948331
telemt_connections_bad_total 6495
telemt_handshake_timeouts_total 26466
telemt_upstream_connect_attempt_total 19002
telemt_upstream_connect_success_total 18526
telemt_upstream_connect_fail_total 476
telemt_upstream_connect_attempts_per_request{bucket="1"} 19002
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9672
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8694
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 476
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 169
telemt_me_reconnect_attempts_total 29296
telemt_me_reconnect_success_total 12181
telemt_me_reader_eof_total 13294
telemt_me_idle_close_by_peer_total 13293
telemt_me_route_drop_no_conn_total 437868
telemt_me_route_drop_channel_closed_total 118
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 870719
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5833
telemt_desync_full_logged_total 1637
telemt_desync_suppressed_total 4196
telemt_desync_frames_bucket_total{bucket="1_2"} 1633
telemt_desync_frames_bucket_total{bucket="3_10"} 2259
telemt_desync_frames_bucket_total{bucket="gt_10"} 1941
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 12884
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 12159
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 703
telemt_user_connections_total{user="hello"} 864994
telemt_user_connections_current{user="hello"} 1268
telemt_user_octets_from_client{user="hello"} 13398071719 (12.48 GB)
telemt_user_octets_to_client{user="hello"} 290687420215 (270.72 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 384
telemt_user_unique_ips_recent_window{user="hello"} 193
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 80479.0 (22h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 738219
telemt_connections_bad_total 41772
telemt_handshake_timeouts_total 29659
telemt_upstream_connect_attempt_total 252266
telemt_upstream_connect_success_total 251583
telemt_upstream_connect_fail_total 677
telemt_upstream_connect_attempts_per_request{bucket="1"} 252260
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 207946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20922
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22713
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 677
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 48458
telemt_me_reconnect_success_total 13565
telemt_me_reader_eof_total 15207
telemt_me_idle_close_by_peer_total 15207
telemt_me_route_drop_no_conn_total 215563
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 399793
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1525
telemt_desync_full_logged_total 482
telemt_desync_suppressed_total 1043
telemt_desync_frames_bucket_total{bucket="1_2"} 345
telemt_desync_frames_bucket_total{bucket="3_10"} 663
telemt_desync_frames_bucket_total{bucket="gt_10"} 517
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14818
telemt_me_refill_failed_total 1086
telemt_me_writer_restored_same_endpoint_total 13549
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1253
telemt_user_connections_total{user="hello"} 633667
telemt_user_connections_current{user="hello"} 2798
telemt_user_octets_from_client{user="hello"} 8165317433 (7.60 GB)
telemt_user_octets_to_client{user="hello"} 172298990749 (160.47 GB)
telemt_user_msgs_from_client{user="hello"} 3674249
telemt_user_msgs_to_client{user="hello"} 15362988
telemt_user_unique_ips_current{user="hello"} 526
telemt_user_unique_ips_recent_window{user="hello"} 335
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 80254.4 (22h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 371391
telemt_connections_bad_total 9955
telemt_handshake_timeouts_total 20159
telemt_upstream_connect_attempt_total 20299
telemt_upstream_connect_success_total 20186
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 20299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10943
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 36753
telemt_me_reconnect_success_total 16087
telemt_me_reader_eof_total 17605
telemt_me_idle_close_by_peer_total 17602
telemt_me_route_drop_no_conn_total 186498
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 324198
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 965
telemt_desync_full_logged_total 293
telemt_desync_suppressed_total 672
telemt_desync_frames_bucket_total{bucket="1_2"} 324
telemt_desync_frames_bucket_total{bucket="3_10"} 426
telemt_desync_frames_bucket_total{bucket="gt_10"} 215
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 16947
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 16075
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 860
telemt_user_connections_total{user="hello"} 322361
telemt_user_connections_current{user="hello"} 1755
telemt_user_octets_from_client{user="hello"} 22792723980 (21.23 GB)
telemt_user_octets_to_client{user="hello"} 104079418200 (96.93 GB)
telemt_user_unique_ips_current{user="hello"} 430
telemt_user_unique_ips_recent_window{user="hello"} 236
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 80313.4 (22h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 810965
telemt_connections_bad_total 15035
telemt_handshake_timeouts_total 15774
telemt_upstream_connect_attempt_total 80089
telemt_upstream_connect_success_total 79697
telemt_upstream_connect_fail_total 392
telemt_upstream_connect_attempts_per_request{bucket="1"} 80089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68577
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10776
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 316
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 392
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 32565
telemt_me_reconnect_success_total 12270
telemt_me_reader_eof_total 13564
telemt_me_idle_close_by_peer_total 13563
telemt_me_route_drop_no_conn_total 306030
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 642735
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2055
telemt_desync_full_logged_total 680
telemt_desync_suppressed_total 1375
telemt_desync_frames_bucket_total{bucket="1_2"} 506
telemt_desync_frames_bucket_total{bucket="3_10"} 927
telemt_desync_frames_bucket_total{bucket="gt_10"} 622
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 13119
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12261
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 849
telemt_user_connections_total{user="hello"} 705886
telemt_user_connections_current{user="hello"} 2246
telemt_user_octets_from_client{user="hello"} 8697603523 (8.10 GB)
telemt_user_octets_to_client{user="hello"} 222548287925 (207.26 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 496
telemt_user_unique_ips_recent_window{user="hello"} 249
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 80285.2 (22h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 408377
telemt_connections_bad_total 68280
telemt_handshake_timeouts_total 4182
telemt_upstream_connect_attempt_total 38404
telemt_upstream_connect_success_total 37906
telemt_upstream_connect_fail_total 498
telemt_upstream_connect_attempts_per_request{bucket="1"} 38404
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12669
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 351
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 498
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 48655
telemt_me_reconnect_success_total 17363
telemt_me_reader_eof_total 18936
telemt_me_idle_close_by_peer_total 18934
telemt_me_route_drop_no_conn_total 118044
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 301876
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1379
telemt_desync_full_logged_total 318
telemt_desync_suppressed_total 1061
telemt_desync_frames_bucket_total{bucket="1_2"} 619
telemt_desync_frames_bucket_total{bucket="3_10"} 547
telemt_desync_frames_bucket_total{bucket="gt_10"} 213
telemt_pool_swap_total 37
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18626
telemt_me_refill_failed_total 973
telemt_me_writer_restored_same_endpoint_total 17355
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1263
telemt_user_connections_total{user="hello"} 318561
telemt_user_connections_current{user="hello"} 2148
telemt_user_octets_from_client{user="hello"} 4627126396 (4.31 GB)
telemt_user_octets_to_client{user="hello"} 134891226284 (125.63 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 492
telemt_user_unique_ips_recent_window{user="hello"} 278
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 80447.6 (22h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 806907
telemt_connections_bad_total 60223
telemt_handshake_timeouts_total 7612
telemt_upstream_connect_attempt_total 16245
telemt_upstream_connect_success_total 16155
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 16245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8342
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_timeout_total 117
telemt_me_reconnect_attempts_total 23367
telemt_me_reconnect_success_total 12100
telemt_me_reader_eof_total 13168
telemt_me_idle_close_by_peer_total 13166
telemt_me_route_drop_no_conn_total 602721
telemt_me_route_drop_channel_closed_total 69
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 830741
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1407
telemt_desync_full_logged_total 493
telemt_desync_suppressed_total 914
telemt_desync_frames_bucket_total{bucket="1_2"} 333
telemt_desync_frames_bucket_total{bucket="3_10"} 548
telemt_desync_frames_bucket_total{bucket="gt_10"} 526
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 12650
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 12086
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 550
telemt_user_connections_total{user="hello"} 697599
telemt_user_connections_current{user="hello"} 953
telemt_user_octets_from_client{user="hello"} 10210205988 (9.51 GB)
telemt_user_octets_to_client{user="hello"} 309434733212 (288.18 GB)
telemt_user_unique_ips_current{user="hello"} 329
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 28213.3 (7h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78342
telemt_connections_bad_total 5207
telemt_handshake_timeouts_total 585
telemt_upstream_connect_attempt_total 14076
telemt_upstream_connect_success_total 13958
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 14076
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6378
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 23924
telemt_me_reconnect_success_total 12349
telemt_me_reader_eof_total 13077
telemt_me_idle_close_by_peer_total 13077
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 20576
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67647
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 105
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 77
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 41
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 12855
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 12329
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 506
telemt_user_connections_total{user="hello"} 67636
telemt_user_connections_current{user="hello"} 1490
telemt_user_octets_from_client{user="hello"} 3626157597 (3.38 GB)
telemt_user_octets_to_client{user="hello"} 73451074246 (68.41 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 316
telemt_user_unique_ips_recent_window{user="hello"} 186
```