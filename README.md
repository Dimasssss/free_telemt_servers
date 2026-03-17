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

# Server Metrics 2026-03-17 04:52:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 36443.2 (10h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194638
telemt_connections_bad_total 3048
telemt_handshake_timeouts_total 7042
telemt_upstream_connect_attempt_total 7773
telemt_upstream_connect_success_total 7730
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 7773
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3511
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4214
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5929
telemt_me_reconnect_success_total 5909
telemt_me_reader_eof_total 6285
telemt_me_idle_close_by_peer_total 6285
telemt_me_route_drop_no_conn_total 61718
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 176273
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1128
telemt_desync_full_logged_total 392
telemt_desync_suppressed_total 736
telemt_desync_frames_bucket_total{bucket="1_2"} 258
telemt_desync_frames_bucket_total{bucket="3_10"} 577
telemt_desync_frames_bucket_total{bucket="gt_10"} 293
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 5965
telemt_me_writer_restored_same_endpoint_total 5888
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 176080
telemt_user_connections_current{user="hello"} 486
telemt_user_octets_from_client{user="hello"} 2470576180 (2.30 GB)
telemt_user_octets_to_client{user="hello"} 80134616872 (74.63 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 36694.4 (10h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108956
telemt_connections_bad_total 2181
telemt_handshake_timeouts_total 3657
telemt_upstream_connect_attempt_total 10199
telemt_upstream_connect_success_total 10068
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 10199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5809
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_reconnect_attempts_total 9428
telemt_me_reconnect_success_total 8258
telemt_me_reader_eof_total 8735
telemt_me_idle_close_by_peer_total 8735
telemt_me_route_drop_no_conn_total 44393
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98732
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 267
telemt_desync_full_logged_total 92
telemt_desync_suppressed_total 175
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 8371
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 8242
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 98734
telemt_user_connections_current{user="hello"} 250
telemt_user_octets_from_client{user="hello"} 1328957532 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 44347867224 (41.30 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 36471.2 (10h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69930
telemt_connections_bad_total 977
telemt_handshake_timeouts_total 2415
telemt_upstream_connect_attempt_total 9762
telemt_upstream_connect_success_total 9710
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 9762
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4316
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5332
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 7914
telemt_me_reconnect_success_total 7871
telemt_me_reader_eof_total 8422
telemt_me_idle_close_by_peer_total 8422
telemt_me_route_drop_no_conn_total 23170
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59598
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 42
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 7968
telemt_me_writer_restored_same_endpoint_total 7860
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 59581
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 5907872016 (5.50 GB)
telemt_user_octets_to_client{user="hello"} 19352230620 (18.02 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 36529.7 (10h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113486
telemt_connections_bad_total 3628
telemt_handshake_timeouts_total 3088
telemt_upstream_connect_attempt_total 8388
telemt_upstream_connect_success_total 8317
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 8388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4371
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_reconnect_attempts_total 6491
telemt_me_reconnect_success_total 6442
telemt_me_reader_eof_total 6860
telemt_me_idle_close_by_peer_total 6860
telemt_me_route_drop_no_conn_total 38175
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 103384
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 182
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 123
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 6538
telemt_me_writer_restored_same_endpoint_total 6435
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 103403
telemt_user_connections_current{user="hello"} 294
telemt_user_octets_from_client{user="hello"} 1126678686 (1.05 GB)
telemt_user_octets_to_client{user="hello"} 47588253105 (44.32 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 36501.7 (10h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84673
telemt_connections_bad_total 21376
telemt_handshake_timeouts_total 1405
telemt_upstream_connect_attempt_total 10822
telemt_upstream_connect_success_total 10687
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 10822
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4788
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5756
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_reconnect_attempts_total 11113
telemt_me_reconnect_success_total 8861
telemt_me_reader_eof_total 9361
telemt_me_idle_close_by_peer_total 9361
telemt_me_route_drop_no_conn_total 23601
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59640
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 9049
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 8853
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 59636
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 666168216 (635.31 MB)
telemt_user_octets_to_client{user="hello"} 23632711888 (22.01 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 36662.9 (10h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216954
telemt_connections_bad_total 29446
telemt_handshake_timeouts_total 1453
telemt_upstream_connect_attempt_total 7594
telemt_upstream_connect_success_total 7554
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 7594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3610
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3938
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 5761
telemt_me_reconnect_success_total 5736
telemt_me_reader_eof_total 6155
telemt_me_idle_close_by_peer_total 6155
telemt_me_route_drop_no_conn_total 193195
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 257529
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 177
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 5820
telemt_me_writer_restored_same_endpoint_total 5726
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 179781
telemt_user_connections_current{user="hello"} 445
telemt_user_octets_from_client{user="hello"} 2799313392 (2.61 GB)
telemt_user_octets_to_client{user="hello"} 139706420844 (130.11 GB)
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 24669.2 (6h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183
telemt_connections_bad_total 122
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 12425
telemt_upstream_connect_success_total 12425
telemt_upstream_connect_attempts_per_request{bucket="1"} 12425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5203
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 11187
telemt_me_reconnect_success_total 11126
telemt_me_reader_eof_total 12232
telemt_me_idle_close_by_peer_total 12232
telemt_me_route_drop_no_conn_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 11230
telemt_me_writer_restored_same_endpoint_total 11126
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 157584760 (150.28 MB)
telemt_user_octets_to_client{user="hello"} 24357516 (23.23 MB)
```