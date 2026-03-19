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

# Server Metrics 2026-03-19 00:41:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 10376.3 (2h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118606
telemt_connections_bad_total 13875
telemt_connections_current 643
telemt_connections_me_current 643
telemt_handshake_timeouts_total 1177
telemt_upstream_connect_attempt_total 2069
telemt_upstream_connect_success_total 2032
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 2069
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1065
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1496
telemt_me_reconnect_success_total 1491
telemt_me_reader_eof_total 1535
telemt_me_idle_close_by_peer_total 1535
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 37171
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98369
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 571
telemt_desync_full_logged_total 164
telemt_desync_suppressed_total 407
telemt_desync_frames_bucket_total{bucket="1_2"} 187
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 136
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1492
telemt_me_writer_restored_same_endpoint_total 1479
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 95602
telemt_user_connections_current{user="hello"} 643
telemt_user_octets_from_client{user="hello"} 893465304 (852.07 MB)
telemt_user_octets_to_client{user="hello"} 36020441228 (33.55 GB)
telemt_user_unique_ips_current{user="hello"} 266
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 10380.0 (2h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 248854
telemt_connections_bad_total 19187
telemt_connections_current 1523
telemt_connections_me_current 1523
telemt_handshake_timeouts_total 2846
telemt_upstream_connect_attempt_total 1957
telemt_upstream_connect_success_total 1916
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 1957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1002
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_reconnect_attempts_total 1374
telemt_me_reconnect_success_total 1370
telemt_me_reader_eof_total 1435
telemt_me_idle_close_by_peer_total 1435
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 75486
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 212743
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 816
telemt_desync_full_logged_total 279
telemt_desync_suppressed_total 537
telemt_desync_frames_bucket_total{bucket="1_2"} 182
telemt_desync_frames_bucket_total{bucket="3_10"} 286
telemt_desync_frames_bucket_total{bucket="gt_10"} 348
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1393
telemt_me_writer_restored_same_endpoint_total 1357
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 212786
telemt_user_connections_current{user="hello"} 1523
telemt_user_octets_from_client{user="hello"} 10720233592 (9.98 GB)
telemt_user_octets_to_client{user="hello"} 80002037284 (74.51 GB)
telemt_user_unique_ips_current{user="hello"} 597
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 10377.4 (2h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 196467
telemt_connections_bad_total 31893
telemt_connections_current 1140
telemt_connections_me_current 1140
telemt_handshake_timeouts_total 5450
telemt_upstream_connect_attempt_total 2034
telemt_upstream_connect_success_total 2034
telemt_upstream_connect_attempts_per_request{bucket="1"} 2034
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1028
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1002
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1492
telemt_me_reconnect_success_total 1488
telemt_me_reader_eof_total 1554
telemt_me_idle_close_by_peer_total 1554
telemt_me_route_drop_no_conn_total 64061
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 153101
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 681
telemt_desync_full_logged_total 257
telemt_desync_suppressed_total 424
telemt_desync_frames_bucket_total{bucket="1_2"} 139
telemt_desync_frames_bucket_total{bucket="3_10"} 272
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1506
telemt_me_writer_restored_same_endpoint_total 1472
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 153101
telemt_user_connections_current{user="hello"} 1140
telemt_user_octets_from_client{user="hello"} 1980068472 (1.84 GB)
telemt_user_octets_to_client{user="hello"} 88750619528 (82.66 GB)
telemt_user_unique_ips_current{user="hello"} 484
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 10430.5 (2h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 204231
telemt_connections_bad_total 26422
telemt_connections_current 916
telemt_connections_me_current 916
telemt_handshake_timeouts_total 3585
telemt_upstream_connect_attempt_total 1934
telemt_upstream_connect_success_total 1934
telemt_upstream_connect_attempts_per_request{bucket="1"} 1934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 915
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 1393
telemt_me_reconnect_success_total 1387
telemt_me_reader_eof_total 1445
telemt_me_idle_close_by_peer_total 1445
telemt_me_route_drop_no_conn_total 72526
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 156907
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 424
telemt_desync_full_logged_total 150
telemt_desync_suppressed_total 274
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 172
telemt_desync_frames_bucket_total{bucket="gt_10"} 173
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1403
telemt_me_writer_restored_same_endpoint_total 1363
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 156828
telemt_user_connections_current{user="hello"} 916
telemt_user_octets_from_client{user="hello"} 1617799480 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 54915596724 (51.14 GB)
telemt_user_unique_ips_current{user="hello"} 395
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 10373.9 (2h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 215373
telemt_connections_bad_total 11898
telemt_connections_current 1140
telemt_connections_me_current 1140
telemt_handshake_timeouts_total 7140
telemt_upstream_connect_attempt_total 1947
telemt_upstream_connect_success_total 1935
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1947
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 989
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 1393
telemt_me_reconnect_success_total 1385
telemt_me_reader_eof_total 1444
telemt_me_idle_close_by_peer_total 1444
telemt_me_route_drop_no_conn_total 68266
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165460
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 655
telemt_desync_full_logged_total 259
telemt_desync_suppressed_total 396
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 261
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1391
telemt_me_writer_restored_same_endpoint_total 1361
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 165389
telemt_user_connections_current{user="hello"} 1140
telemt_user_octets_from_client{user="hello"} 2128604536 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 100946702900 (94.01 GB)
telemt_user_unique_ips_current{user="hello"} 513
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 10385.4 (2h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53756
telemt_connections_bad_total 9054
telemt_connections_current 330
telemt_connections_me_current 330
telemt_handshake_timeouts_total 165
telemt_upstream_connect_attempt_total 3083
telemt_upstream_connect_success_total 2986
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 3083
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1533
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_reconnect_attempts_total 4273
telemt_me_reconnect_success_total 2446
telemt_me_reader_eof_total 2545
telemt_me_idle_close_by_peer_total 2545
telemt_me_route_drop_no_conn_total 19964
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43252
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 27
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2486
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 2416
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 43252
telemt_user_connections_current{user="hello"} 330
telemt_user_octets_from_client{user="hello"} 533611608 (508.89 MB)
telemt_user_octets_to_client{user="hello"} 27945698352 (26.03 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 10376.2 (2h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 154983
telemt_connections_bad_total 18856
telemt_connections_current 1009
telemt_connections_me_current 1009
telemt_handshake_timeouts_total 6109
telemt_upstream_connect_attempt_total 2176
telemt_upstream_connect_success_total 2176
telemt_upstream_connect_attempts_per_request{bucket="1"} 2176
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1054
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1634
telemt_me_reconnect_success_total 1629
telemt_me_reader_eof_total 1701
telemt_me_idle_close_by_peer_total 1701
telemt_me_route_drop_no_conn_total 46337
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 127090
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 875
telemt_desync_full_logged_total 349
telemt_desync_suppressed_total 526
telemt_desync_frames_bucket_total{bucket="1_2"} 148
telemt_desync_frames_bucket_total{bucket="3_10"} 358
telemt_desync_frames_bucket_total{bucket="gt_10"} 369
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1647
telemt_me_writer_restored_same_endpoint_total 1614
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 127113
telemt_user_connections_current{user="hello"} 1009
telemt_user_octets_from_client{user="hello"} 1243914288 (1.16 GB)
telemt_user_octets_to_client{user="hello"} 67744479252 (63.09 GB)
telemt_user_unique_ips_current{user="hello"} 436
telemt_user_unique_ips_recent_window{user="hello"} 94
```