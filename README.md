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

# Server Metrics 2026-03-18 13:09:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 16138.8 (4h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 598589
telemt_connections_bad_total 21377
telemt_handshake_timeouts_total 16238
telemt_upstream_connect_attempt_total 66115
telemt_upstream_connect_success_total 65161
telemt_upstream_connect_fail_total 954
telemt_upstream_connect_attempts_per_request{bucket="1"} 66115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4057
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 954
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 514020
telemt_me_reconnect_success_total 2372
telemt_me_reader_eof_total 2523
telemt_me_idle_close_by_peer_total 2521
telemt_me_route_drop_no_conn_total 360257
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 461004
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2084
telemt_desync_full_logged_total 693
telemt_desync_suppressed_total 1391
telemt_desync_frames_bucket_total{bucket="1_2"} 586
telemt_desync_frames_bucket_total{bucket="3_10"} 737
telemt_desync_frames_bucket_total{bucket="gt_10"} 761
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2538
telemt_me_refill_failed_total 16672
telemt_me_writer_restored_same_endpoint_total 2267
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 519212
telemt_user_connections_current{user="hello"} 1869
telemt_user_octets_from_client{user="hello"} 6924417028 (6.45 GB)
telemt_user_octets_to_client{user="hello"} 132346870257 (123.26 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 575
telemt_user_unique_ips_recent_window{user="hello"} 264
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 16170.5 (4h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1604647
telemt_connections_bad_total 114574
telemt_handshake_timeouts_total 35818
telemt_upstream_connect_attempt_total 2837
telemt_upstream_connect_success_total 2825
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2837
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1501
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1308
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3097
telemt_me_reconnect_success_total 1955
telemt_me_reader_eof_total 2030
telemt_me_idle_close_by_peer_total 2029
telemt_me_route_drop_no_conn_total 1346338
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1377617
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4300
telemt_desync_full_logged_total 1330
telemt_desync_suppressed_total 2970
telemt_desync_frames_bucket_total{bucket="1_2"} 877
telemt_desync_frames_bucket_total{bucket="3_10"} 1748
telemt_desync_frames_bucket_total{bucket="gt_10"} 1675
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2001
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 1954
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 1376590
telemt_user_connections_current{user="hello"} 4577
telemt_user_octets_from_client{user="hello"} 34390246736 (32.03 GB)
telemt_user_octets_to_client{user="hello"} 412155246840 (383.85 GB)
telemt_user_unique_ips_current{user="hello"} 1352
telemt_user_unique_ips_recent_window{user="hello"} 661
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 16085.5 (4h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1143458
telemt_connections_bad_total 84199
telemt_handshake_timeouts_total 27093
telemt_upstream_connect_attempt_total 11337
telemt_upstream_connect_success_total 11337
telemt_upstream_connect_attempts_per_request{bucket="1"} 11337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8557
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2768
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 109
telemt_me_reconnect_attempts_total 607975
telemt_me_reconnect_success_total 2275
telemt_me_reader_eof_total 2303
telemt_me_idle_close_by_peer_total 2302
telemt_me_route_drop_no_conn_total 494297
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 879812
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2708
telemt_desync_full_logged_total 906
telemt_desync_suppressed_total 1802
telemt_desync_frames_bucket_total{bucket="1_2"} 773
telemt_desync_frames_bucket_total{bucket="3_10"} 980
telemt_desync_frames_bucket_total{bucket="gt_10"} 955
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2289
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 2240
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 887300
telemt_user_connections_current{user="hello"} 3279
telemt_user_octets_from_client{user="hello"} 11396386623 (10.61 GB)
telemt_user_octets_to_client{user="hello"} 372664407484 (347.07 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 1001
telemt_user_unique_ips_recent_window{user="hello"} 456
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 16115.6 (4h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1895919
telemt_connections_bad_total 29488
telemt_handshake_timeouts_total 171408
telemt_upstream_connect_attempt_total 12500
telemt_upstream_connect_success_total 12302
telemt_upstream_connect_fail_total 198
telemt_upstream_connect_attempts_per_request{bucket="1"} 12500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10952
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1311
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 198
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2831186
telemt_me_reconnect_success_total 1180
telemt_me_reader_eof_total 1761
telemt_me_idle_close_by_peer_total 1761
telemt_me_route_drop_no_conn_total 2896574
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1545487
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
telemt_desync_total 3262
telemt_desync_full_logged_total 991
telemt_desync_suppressed_total 2271
telemt_desync_frames_bucket_total{bucket="1_2"} 841
telemt_desync_frames_bucket_total{bucket="3_10"} 1365
telemt_desync_frames_bucket_total{bucket="gt_10"} 1056
telemt_me_writer_removed_unexpected_total 1810
telemt_me_refill_failed_total 100175
telemt_me_writer_restored_same_endpoint_total 1085
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 630
telemt_user_connections_total{user="hello"} 1564034
telemt_user_connections_current{user="hello"} 3162
telemt_user_octets_from_client{user="hello"} 26130788830 (24.34 GB)
telemt_user_octets_to_client{user="hello"} 233063332561 (217.06 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 886
telemt_user_unique_ips_recent_window{user="hello"} 454
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 16010.4 (4h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1254250
telemt_connections_bad_total 72347
telemt_handshake_timeouts_total 20999
telemt_upstream_connect_attempt_total 12287
telemt_upstream_connect_success_total 12286
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10494
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1563
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 2986376
telemt_me_reconnect_success_total 1944
telemt_me_reader_eof_total 2024
telemt_me_idle_close_by_peer_total 2024
telemt_me_route_drop_no_conn_total 1198707
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1057990
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3267
telemt_desync_full_logged_total 1098
telemt_desync_suppressed_total 2169
telemt_desync_frames_bucket_total{bucket="1_2"} 481
telemt_desync_frames_bucket_total{bucket="3_10"} 1274
telemt_desync_frames_bucket_total{bucket="gt_10"} 1512
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2002
telemt_me_refill_failed_total 107230
telemt_me_writer_restored_same_endpoint_total 1829
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 1058086
telemt_user_connections_current{user="hello"} 2870
telemt_user_octets_from_client{user="hello"} 16047686793 (14.95 GB)
telemt_user_octets_to_client{user="hello"} 381226523245 (355.04 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 983
telemt_user_unique_ips_recent_window{user="hello"} 480
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 15895.9 (4h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 348479
telemt_connections_bad_total 32669
telemt_handshake_timeouts_total 2568
telemt_upstream_connect_attempt_total 2951
telemt_upstream_connect_success_total 2951
telemt_upstream_connect_attempts_per_request{bucket="1"} 2951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1349
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1592
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 8529
telemt_me_reconnect_success_total 2077
telemt_me_reader_eof_total 2313
telemt_me_idle_close_by_peer_total 2312
telemt_me_route_drop_no_conn_total 203182
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 298370
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 768
telemt_desync_full_logged_total 272
telemt_desync_suppressed_total 496
telemt_desync_frames_bucket_total{bucket="1_2"} 154
telemt_desync_frames_bucket_total{bucket="3_10"} 282
telemt_desync_frames_bucket_total{bucket="gt_10"} 332
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2296
telemt_me_refill_failed_total 200
telemt_me_writer_restored_same_endpoint_total 2068
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 219
telemt_user_connections_total{user="hello"} 288645
telemt_user_connections_current{user="hello"} 973
telemt_user_octets_from_client{user="hello"} 4641866776 (4.32 GB)
telemt_user_octets_to_client{user="hello"} 59052691412 (55.00 GB)
telemt_user_unique_ips_current{user="hello"} 321
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 15966.6 (4h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1014745
telemt_connections_bad_total 117580
telemt_handshake_timeouts_total 20803
telemt_upstream_connect_attempt_total 2915
telemt_upstream_connect_success_total 2888
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 2915
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1277
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 2061
telemt_me_reconnect_success_total 2015
telemt_me_reader_eof_total 2069
telemt_me_idle_close_by_peer_total 2069
telemt_me_route_drop_no_conn_total 602803
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 801134
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2768
telemt_desync_full_logged_total 926
telemt_desync_suppressed_total 1842
telemt_desync_frames_bucket_total{bucket="1_2"} 508
telemt_desync_frames_bucket_total{bucket="3_10"} 949
telemt_desync_frames_bucket_total{bucket="gt_10"} 1311
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2033
telemt_me_writer_restored_same_endpoint_total 2005
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 800602
telemt_user_connections_current{user="hello"} 2900
telemt_user_octets_from_client{user="hello"} 15997486496 (14.90 GB)
telemt_user_octets_to_client{user="hello"} 367449124904 (342.21 GB)
telemt_user_unique_ips_current{user="hello"} 869
telemt_user_unique_ips_recent_window{user="hello"} 417
```