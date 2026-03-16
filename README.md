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

# Server Metrics 2026-03-16 09:31:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 127007.1 (35h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 610051
telemt_connections_bad_total 10153
telemt_handshake_timeouts_total 21561
telemt_upstream_connect_attempt_total 29842
telemt_upstream_connect_success_total 29700
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 29842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16430
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 28050
telemt_me_reconnect_success_total 23393
telemt_me_reader_eof_total 25012
telemt_me_idle_close_by_peer_total 25012
telemt_me_route_drop_no_conn_total 537925
telemt_me_route_drop_channel_closed_total 85
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 598684
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2855
telemt_desync_full_logged_total 1102
telemt_desync_suppressed_total 1753
telemt_desync_frames_bucket_total{bucket="1_2"} 628
telemt_desync_frames_bucket_total{bucket="3_10"} 1098
telemt_desync_frames_bucket_total{bucket="gt_10"} 1129
telemt_pool_swap_total 121
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23794
telemt_me_refill_failed_total 142
telemt_me_writer_restored_same_endpoint_total 23359
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 401
telemt_user_connections_total{user="hello"} 537452
telemt_user_connections_current{user="hello"} 520
telemt_user_octets_from_client{user="hello"} 10529535056 (9.81 GB)
telemt_user_octets_to_client{user="hello"} 337333481976 (314.17 GB)
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 127014.3 (35h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 251044
telemt_connections_bad_total 3291
telemt_handshake_timeouts_total 15466
telemt_upstream_connect_attempt_total 34068
telemt_upstream_connect_success_total 33993
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 34068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18656
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 687
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 36564
telemt_me_reconnect_success_total 27273
telemt_me_reader_eof_total 29228
telemt_me_idle_close_by_peer_total 29227
telemt_me_route_drop_no_conn_total 120080
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 223551
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 193
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 133
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 86
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 27942
telemt_me_refill_failed_total 282
telemt_me_writer_restored_same_endpoint_total 27257
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 669
telemt_user_connections_total{user="hello"} 223091
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 4936341133 (4.60 GB)
telemt_user_octets_to_client{user="hello"} 122129632644 (113.74 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 127007.1 (35h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 260737
telemt_connections_bad_total 5757
telemt_handshake_timeouts_total 5656
telemt_upstream_connect_attempt_total 35289
telemt_upstream_connect_success_total 35281
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 35289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15239
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 36318
telemt_me_reconnect_success_total 28902
telemt_me_reader_eof_total 31084
telemt_me_idle_close_by_peer_total 31083
telemt_me_route_drop_no_conn_total 90388
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 210883
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 100
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 61
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 29419
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 28894
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 517
telemt_user_connections_total{user="hello"} 210582
telemt_user_connections_current{user="hello"} 268
telemt_user_octets_from_client{user="hello"} 17667110785 (16.45 GB)
telemt_user_octets_to_client{user="hello"} 117599673484 (109.52 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 127006.6 (35h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 373305
telemt_connections_bad_total 1381
telemt_handshake_timeouts_total 3219
telemt_upstream_connect_attempt_total 29399
telemt_upstream_connect_success_total 29360
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 29399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15106
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 23189
telemt_me_reconnect_success_total 23035
telemt_me_reader_eof_total 24577
telemt_me_idle_close_by_peer_total 24576
telemt_me_route_drop_no_conn_total 129641
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 345205
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1286
telemt_desync_full_logged_total 442
telemt_desync_suppressed_total 844
telemt_desync_frames_bucket_total{bucket="1_2"} 259
telemt_desync_frames_bucket_total{bucket="3_10"} 547
telemt_desync_frames_bucket_total{bucket="gt_10"} 480
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 23344
telemt_me_writer_restored_same_endpoint_total 23024
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 309
telemt_user_connections_total{user="hello"} 345081
telemt_user_connections_current{user="hello"} 420
telemt_user_octets_from_client{user="hello"} 5871786526 (5.47 GB)
telemt_user_octets_to_client{user="hello"} 140504670436 (130.86 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 102078.0 (28h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 235824
telemt_connections_bad_total 37187
telemt_handshake_timeouts_total 4241
telemt_upstream_connect_attempt_total 29205
telemt_upstream_connect_success_total 29046
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 29205
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12865
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16033
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 118300
telemt_me_reconnect_success_total 23798
telemt_me_reader_eof_total 25276
telemt_me_idle_close_by_peer_total 25276
telemt_me_route_drop_no_conn_total 73792
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 187664
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 612
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 472
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 244
telemt_desync_frames_bucket_total{bucket="gt_10"} 273
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 24002
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 23694
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 187280
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 2468550493 (2.30 GB)
telemt_user_octets_to_client{user="hello"} 81321804811 (75.74 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 127006.2 (35h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 858592
telemt_connections_bad_total 72554
telemt_handshake_timeouts_total 10032
telemt_upstream_connect_attempt_total 26673
telemt_upstream_connect_success_total 26533
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 26673
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12610
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13881
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 21555
telemt_me_reconnect_success_total 20202
telemt_me_reader_eof_total 21551
telemt_me_idle_close_by_peer_total 21551
telemt_me_route_drop_no_conn_total 662879
telemt_me_route_drop_channel_closed_total 117
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 848813
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 336
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 240
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 20484
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 20175
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 282
telemt_user_connections_total{user="hello"} 707457
telemt_user_connections_current{user="hello"} 635
telemt_user_octets_from_client{user="hello"} 15166102912 (14.12 GB)
telemt_user_octets_to_client{user="hello"} 428832852440 (399.38 GB)
telemt_user_unique_ips_current{user="hello"} 223
telemt_user_unique_ips_recent_window{user="hello"} 95
```