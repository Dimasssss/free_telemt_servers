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

# Server Metrics 2026-03-14 22:00:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 31431.3 (8h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146690
telemt_connections_bad_total 16480
telemt_handshake_timeouts_total 1568
telemt_upstream_connect_attempt_total 7098
telemt_upstream_connect_success_total 7096
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7098
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3669
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 224
telemt_me_reconnect_attempts_total 5547
telemt_me_reconnect_success_total 5507
telemt_me_reader_eof_total 5853
telemt_me_idle_close_by_peer_total 5853
telemt_me_route_drop_no_conn_total 53018
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 122097
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 584
telemt_desync_full_logged_total 203
telemt_desync_suppressed_total 381
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 213
telemt_desync_frames_bucket_total{bucket="gt_10"} 241
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 5596
telemt_me_writer_restored_same_endpoint_total 5489
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 122017
telemt_user_connections_current{user="hello"} 259
telemt_user_octets_from_client{user="hello"} 2619919104 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 74151088432 (69.06 GB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 31429.4 (8h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60741
telemt_connections_bad_total 738
telemt_handshake_timeouts_total 1004
telemt_upstream_connect_attempt_total 8150
telemt_upstream_connect_success_total 8098
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 8150
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3362
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4600
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 146
telemt_me_reconnect_attempts_total 9091
telemt_me_reconnect_success_total 6508
telemt_me_reader_eof_total 6931
telemt_me_idle_close_by_peer_total 6931
telemt_me_route_drop_no_conn_total 32597
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56724
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 6675
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 6503
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 56645
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 1400585416 (1.30 GB)
telemt_user_octets_to_client{user="hello"} 26442357664 (24.63 GB)
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 31433.7 (8h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69042
telemt_connections_bad_total 395
telemt_handshake_timeouts_total 1917
telemt_upstream_connect_attempt_total 10257
telemt_upstream_connect_success_total 10153
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 10257
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4686
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5454
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_timeout_total 272
telemt_me_reconnect_attempts_total 106113
telemt_me_reconnect_success_total 8246
telemt_me_reader_eof_total 8813
telemt_me_idle_close_by_peer_total 8813
telemt_me_route_drop_no_conn_total 25597
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63276
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 8533
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 8200
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 63339
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 3975095437 (3.70 GB)
telemt_user_octets_to_client{user="hello"} 50503066510 (47.03 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 31438.8 (8h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86743
telemt_connections_bad_total 215
telemt_handshake_timeouts_total 619
telemt_upstream_connect_attempt_total 7645
telemt_upstream_connect_success_total 7600
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 7645
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4036
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 212
telemt_me_reconnect_attempts_total 5876
telemt_me_reconnect_success_total 5846
telemt_me_reader_eof_total 6169
telemt_me_idle_close_by_peer_total 6169
telemt_me_route_drop_no_conn_total 37842
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 82260
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 663
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 492
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 279
telemt_desync_frames_bucket_total{bucket="gt_10"} 264
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 5911
telemt_me_writer_restored_same_endpoint_total 5844
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 82304
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 1391608008 (1.30 GB)
telemt_user_octets_to_client{user="hello"} 29999452042 (27.94 GB)
telemt_user_msgs_from_client{user="hello"} 473
telemt_user_msgs_to_client{user="hello"} 2783
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 31431.8 (8h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65753
telemt_connections_bad_total 6120
telemt_handshake_timeouts_total 3389
telemt_upstream_connect_attempt_total 7670
telemt_upstream_connect_success_total 7583
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 7670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3427
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4106
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 233
telemt_me_reconnect_attempts_total 12530
telemt_me_reconnect_success_total 5989
telemt_me_reader_eof_total 6482
telemt_me_idle_close_by_peer_total 6482
telemt_me_route_drop_no_conn_total 21218
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52987
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 270
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 229
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 136
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 6251
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 5985
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 262
telemt_user_connections_total{user="hello"} 52973
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 1415743096 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 32194560328 (29.98 GB)
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 31431.5 (8h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221316
telemt_connections_bad_total 7769
telemt_handshake_timeouts_total 2759
telemt_upstream_connect_attempt_total 6263
telemt_upstream_connect_success_total 6150
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 6263
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3147
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 263
telemt_me_reconnect_attempts_total 9572
telemt_me_reconnect_success_total 4562
telemt_me_reader_eof_total 4931
telemt_me_idle_close_by_peer_total 4931
telemt_me_route_drop_no_conn_total 123809
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 204372
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 116
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 84
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4774
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 4558
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 200855
telemt_user_connections_current{user="hello"} 302
telemt_user_octets_from_client{user="hello"} 6338885228 (5.90 GB)
telemt_user_octets_to_client{user="hello"} 110951148408 (103.33 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 37
```