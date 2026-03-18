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

# Server Metrics 2026-03-18 17:20:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 6934.7 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 209997
telemt_connections_bad_total 14248
telemt_handshake_timeouts_total 5719
telemt_upstream_connect_attempt_total 1114
telemt_upstream_connect_success_total 1114
telemt_upstream_connect_attempts_per_request{bucket="1"} 1114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 530
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 743
telemt_me_reconnect_success_total 741
telemt_me_reader_eof_total 757
telemt_me_idle_close_by_peer_total 757
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 100800
telemt_me_route_drop_channel_closed_total 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 176050
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 978
telemt_desync_full_logged_total 297
telemt_desync_suppressed_total 681
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 322
telemt_desync_frames_bucket_total{bucket="gt_10"} 420
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 759
telemt_me_writer_restored_same_endpoint_total 728
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 175968
telemt_user_connections_current{user="hello"} 1456
telemt_user_octets_from_client{user="hello"} 2415522652 (2.25 GB)
telemt_user_octets_to_client{user="hello"} 59304424436 (55.23 GB)
telemt_user_unique_ips_current{user="hello"} 493
telemt_user_unique_ips_recent_window{user="hello"} 181
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 11763.1 (3h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1165179
telemt_connections_bad_total 74950
telemt_connections_current 3853
telemt_connections_me_current 3853
telemt_handshake_timeouts_total 16937
telemt_upstream_connect_attempt_total 2080
telemt_upstream_connect_success_total 2070
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 2080
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 935
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 1461
telemt_me_reconnect_success_total 1450
telemt_me_reader_eof_total 1407
telemt_me_idle_close_by_peer_total 1406
telemt_me_route_drop_no_conn_total 1070175
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1016740
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3006
telemt_desync_full_logged_total 974
telemt_desync_suppressed_total 2032
telemt_desync_frames_bucket_total{bucket="1_2"} 579
telemt_desync_frames_bucket_total{bucket="3_10"} 1194
telemt_desync_frames_bucket_total{bucket="gt_10"} 1233
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1384
telemt_me_writer_restored_same_endpoint_total 1448
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1015877
telemt_user_connections_current{user="hello"} 3853
telemt_user_octets_from_client{user="hello"} 13490990248 (12.56 GB)
telemt_user_octets_to_client{user="hello"} 306959284064 (285.88 GB)
telemt_user_unique_ips_current{user="hello"} 1211
telemt_user_unique_ips_recent_window{user="hello"} 541
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 11691.2 (3h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 827518
telemt_connections_bad_total 60780
telemt_connections_current 3088
telemt_connections_me_current 3088
telemt_handshake_timeouts_total 18062
telemt_upstream_connect_attempt_total 1611
telemt_upstream_connect_success_total 1603
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1611
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 747
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1011
telemt_me_reconnect_success_total 1001
telemt_me_reader_eof_total 1057
telemt_me_idle_close_by_peer_total 1057
telemt_me_route_drop_no_conn_total 391751
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 692273
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2794
telemt_desync_full_logged_total 848
telemt_desync_suppressed_total 1946
telemt_desync_frames_bucket_total{bucket="1_2"} 655
telemt_desync_frames_bucket_total{bucket="3_10"} 1047
telemt_desync_frames_bucket_total{bucket="gt_10"} 1092
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1035
telemt_me_writer_restored_same_endpoint_total 984
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 691914
telemt_user_connections_current{user="hello"} 3088
telemt_user_octets_from_client{user="hello"} 13326363264 (12.41 GB)
telemt_user_octets_to_client{user="hello"} 293486857792 (273.33 GB)
telemt_user_unique_ips_current{user="hello"} 1000
telemt_user_unique_ips_recent_window{user="hello"} 432
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 12405.8 (3h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1220458
telemt_connections_bad_total 26370
telemt_connections_current 2900
telemt_connections_me_current 2900
telemt_handshake_timeouts_total 14693
telemt_upstream_connect_attempt_total 1929
telemt_upstream_connect_success_total 1916
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 1929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 914
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1277
telemt_me_reconnect_success_total 1262
telemt_me_reader_eof_total 1283
telemt_me_idle_close_by_peer_total 1282
telemt_me_route_drop_no_conn_total 2041273
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1094565
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3984
telemt_desync_full_logged_total 1034
telemt_desync_suppressed_total 2950
telemt_desync_frames_bucket_total{bucket="1_2"} 918
telemt_desync_frames_bucket_total{bucket="3_10"} 1805
telemt_desync_frames_bucket_total{bucket="gt_10"} 1261
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1257
telemt_me_writer_restored_same_endpoint_total 1251
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 1094488
telemt_user_connections_current{user="hello"} 2900
telemt_user_octets_from_client{user="hello"} 9262885356 (8.63 GB)
telemt_user_octets_to_client{user="hello"} 187424748904 (174.55 GB)
telemt_user_unique_ips_current{user="hello"} 885
telemt_user_unique_ips_recent_window{user="hello"} 551
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 6920.8 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 524189
telemt_connections_bad_total 92372
telemt_handshake_timeouts_total 4939
telemt_upstream_connect_attempt_total 1219
telemt_upstream_connect_success_total 1182
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 1218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 1806
telemt_me_reconnect_success_total 805
telemt_me_reader_eof_total 834
telemt_me_idle_close_by_peer_total 834
telemt_me_route_drop_no_conn_total 217104
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 387131
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1482
telemt_desync_full_logged_total 490
telemt_desync_suppressed_total 992
telemt_desync_frames_bucket_total{bucket="1_2"} 271
telemt_desync_frames_bucket_total{bucket="3_10"} 481
telemt_desync_frames_bucket_total{bucket="gt_10"} 730
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 843
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 779
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 386669
telemt_user_connections_current{user="hello"} 3151
telemt_user_octets_from_client{user="hello"} 6191687656 (5.77 GB)
telemt_user_octets_to_client{user="hello"} 161675400228 (150.57 GB)
telemt_user_unique_ips_current{user="hello"} 1065
telemt_user_unique_ips_recent_window{user="hello"} 476
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 11858.1 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 213811
telemt_connections_bad_total 7733
telemt_connections_current 855
telemt_connections_me_current 855
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 2348
telemt_upstream_connect_attempt_total 6229
telemt_upstream_connect_success_total 6216
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 6229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3345
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2820
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 331208
telemt_me_reconnect_success_total 1743
telemt_me_reader_eof_total 1717
telemt_me_idle_close_by_peer_total 1717
telemt_me_route_drop_no_conn_total 118925
telemt_me_route_drop_channel_closed_total 50
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 189613
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 397
telemt_desync_full_logged_total 142
telemt_desync_suppressed_total 255
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 162
telemt_desync_frames_bucket_total{bucket="gt_10"} 167
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1681
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 1732
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 193335
telemt_user_connections_current{user="hello"} 855
telemt_user_octets_from_client{user="hello"} 2748236833 (2.56 GB)
telemt_user_octets_to_client{user="hello"} 40789816673 (37.99 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 10925.1 (3h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 672811
telemt_connections_bad_total 47359
telemt_connections_current 2983
telemt_connections_me_current 2983
telemt_handshake_timeouts_total 13199
telemt_upstream_connect_attempt_total 1963
telemt_upstream_connect_success_total 1962
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 865
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 16871
telemt_me_reconnect_success_total 1358
telemt_me_reader_eof_total 1336
telemt_me_idle_close_by_peer_total 1336
telemt_me_route_drop_no_conn_total 386530
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 562286
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2147
telemt_desync_full_logged_total 734
telemt_desync_suppressed_total 1413
telemt_desync_frames_bucket_total{bucket="1_2"} 521
telemt_desync_frames_bucket_total{bucket="3_10"} 768
telemt_desync_frames_bucket_total{bucket="gt_10"} 858
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1319
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1297
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 561320
telemt_user_connections_current{user="hello"} 2983
telemt_user_octets_from_client{user="hello"} 10485948592 (9.77 GB)
telemt_user_octets_to_client{user="hello"} 271731638360 (253.07 GB)
telemt_user_unique_ips_current{user="hello"} 882
telemt_user_unique_ips_recent_window{user="hello"} 381
```