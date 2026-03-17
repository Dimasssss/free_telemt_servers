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

# Server Metrics 2026-03-17 09:12:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 52030.7 (14h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 397930
telemt_connections_bad_total 3635
telemt_handshake_timeouts_total 11895
telemt_upstream_connect_attempt_total 13367
telemt_upstream_connect_success_total 12937
telemt_upstream_connect_fail_total 430
telemt_upstream_connect_attempts_per_request{bucket="1"} 13367
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5871
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 430
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 9588
telemt_me_reconnect_success_total 8067
telemt_me_reader_eof_total 8572
telemt_me_idle_close_by_peer_total 8571
telemt_me_route_drop_no_conn_total 125237
telemt_me_route_drop_channel_closed_total 30
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 358269
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2766
telemt_desync_full_logged_total 773
telemt_desync_suppressed_total 1993
telemt_desync_frames_bucket_total{bucket="1_2"} 643
telemt_desync_frames_bucket_total{bucket="3_10"} 1282
telemt_desync_frames_bucket_total{bucket="gt_10"} 841
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 8232
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 8045
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 360263
telemt_user_connections_current{user="hello"} 897
telemt_user_octets_from_client{user="hello"} 4985847135 (4.64 GB)
telemt_user_octets_to_client{user="hello"} 142638024675 (132.84 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 323
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 52282.5 (14h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216282
telemt_connections_bad_total 2377
telemt_handshake_timeouts_total 12463
telemt_upstream_connect_attempt_total 13958
telemt_upstream_connect_success_total 13770
telemt_upstream_connect_fail_total 187
telemt_upstream_connect_attempts_per_request{bucket="1"} 13957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7729
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 139
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 187
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 15823
telemt_me_reconnect_success_total 11180
telemt_me_reader_eof_total 11887
telemt_me_idle_close_by_peer_total 11887
telemt_me_route_drop_no_conn_total 78953
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 190813
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 513
telemt_desync_full_logged_total 186
telemt_desync_suppressed_total 327
telemt_desync_frames_bucket_total{bucket="1_2"} 153
telemt_desync_frames_bucket_total{bucket="3_10"} 220
telemt_desync_frames_bucket_total{bucket="gt_10"} 140
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 11438
telemt_me_refill_failed_total 144
telemt_me_writer_restored_same_endpoint_total 11164
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 258
telemt_user_connections_total{user="hello"} 190818
telemt_user_connections_current{user="hello"} 478
telemt_user_octets_from_client{user="hello"} 2270582660 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 75988114516 (70.77 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 52059.0 (14h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133321
telemt_connections_bad_total 7572
telemt_handshake_timeouts_total 8569
telemt_upstream_connect_attempt_total 13801
telemt_upstream_connect_success_total 13730
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 13801
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7605
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 12084
telemt_me_reconnect_success_total 11118
telemt_me_reader_eof_total 11888
telemt_me_idle_close_by_peer_total 11888
telemt_me_route_drop_no_conn_total 40823
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 108012
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 300
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 221
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 124
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 11292
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 11107
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 174
telemt_user_connections_total{user="hello"} 107937
telemt_user_connections_current{user="hello"} 300
telemt_user_octets_from_client{user="hello"} 7220516848 (6.72 GB)
telemt_user_octets_to_client{user="hello"} 34060470676 (31.72 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 52117.6 (14h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 290628
telemt_connections_bad_total 6179
telemt_handshake_timeouts_total 10674
telemt_upstream_connect_attempt_total 11857
telemt_upstream_connect_success_total 11750
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 11857
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5545
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6131
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 10181
telemt_me_reconnect_success_total 9103
telemt_me_reader_eof_total 9688
telemt_me_idle_close_by_peer_total 9688
telemt_me_route_drop_no_conn_total 80049
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 230966
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 478
telemt_desync_full_logged_total 180
telemt_desync_suppressed_total 298
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 207
telemt_desync_frames_bucket_total{bucket="gt_10"} 151
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 9277
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 9095
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 174
telemt_user_connections_total{user="hello"} 230921
telemt_user_connections_current{user="hello"} 685
telemt_user_octets_from_client{user="hello"} 2458922782 (2.29 GB)
telemt_user_octets_to_client{user="hello"} 94998242445 (88.47 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 52089.6 (14h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164201
telemt_connections_bad_total 44480
telemt_handshake_timeouts_total 2741
telemt_upstream_connect_attempt_total 15860
telemt_upstream_connect_success_total 15651
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 15860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8449
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 197
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_reconnect_attempts_total 20059
telemt_me_reconnect_success_total 12949
telemt_me_reader_eof_total 13736
telemt_me_idle_close_by_peer_total 13736
telemt_me_route_drop_no_conn_total 42950
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111951
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 340
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 254
telemt_desync_frames_bucket_total{bucket="1_2"} 162
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 13335
telemt_me_refill_failed_total 220
telemt_me_writer_restored_same_endpoint_total 12941
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 386
telemt_user_connections_total{user="hello"} 111979
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 1758770447 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 50998976570 (47.50 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 52250.9 (14h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 390257
telemt_connections_bad_total 46781
telemt_handshake_timeouts_total 3894
telemt_upstream_connect_attempt_total 10700
telemt_upstream_connect_success_total 10642
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 10700
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5217
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5409
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 11920
telemt_me_reconnect_success_total 8042
telemt_me_reader_eof_total 8687
telemt_me_idle_close_by_peer_total 8687
telemt_me_route_drop_no_conn_total 265026
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 395807
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 538
telemt_desync_full_logged_total 216
telemt_desync_suppressed_total 322
telemt_desync_frames_bucket_total{bucket="1_2"} 153
telemt_desync_frames_bucket_total{bucket="3_10"} 196
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 8282
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 8028
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 317701
telemt_user_connections_current{user="hello"} 787
telemt_user_octets_from_client{user="hello"} 4594208212 (4.28 GB)
telemt_user_octets_to_client{user="hello"} 179484514628 (167.16 GB)
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 22.3 (0h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110
telemt_upstream_connect_attempt_total 66
telemt_upstream_connect_success_total 64
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 66
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_route_drop_no_conn_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 88
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_user_connections_total{user="hello"} 88
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 95216 (92.98 KB)
telemt_user_octets_to_client{user="hello"} 1415112 (1.35 MB)
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 12
```