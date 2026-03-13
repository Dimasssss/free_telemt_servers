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

# Server Metrics 2026-03-13 05:40:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 79645.9 (22h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 302419
telemt_connections_bad_total 3068
telemt_handshake_timeouts_total 6199
telemt_upstream_connect_attempt_total 20048
telemt_upstream_connect_success_total 19954
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 20048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8935
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10971
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1577
telemt_me_reconnect_attempts_total 19448
telemt_me_reconnect_success_total 15949
telemt_me_reader_eof_total 17059
telemt_me_idle_close_by_peer_total 17058
telemt_me_route_drop_no_conn_total 94366
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 254894
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 869
telemt_desync_full_logged_total 324
telemt_desync_suppressed_total 545
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 315
telemt_desync_frames_bucket_total{bucket="gt_10"} 379
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 16232
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 15933
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 283
telemt_user_connections_total{user="hello"} 254831
telemt_user_connections_current{user="hello"} 269
telemt_user_octets_from_client{user="hello"} 4339804804 (4.04 GB)
telemt_user_octets_to_client{user="hello"} 123724039980 (115.23 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 79538.7 (22h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137999
telemt_connections_bad_total 759
telemt_handshake_timeouts_total 1041
telemt_upstream_connect_attempt_total 42152
telemt_upstream_connect_success_total 41615
telemt_upstream_connect_fail_total 537
telemt_upstream_connect_attempts_per_request{bucket="1"} 42152
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16328
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 508
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 537
telemt_me_keepalive_timeout_total 591
telemt_me_reconnect_attempts_total 67693
telemt_me_reconnect_success_total 21129
telemt_me_reader_eof_total 23233
telemt_me_idle_close_by_peer_total 23233
telemt_me_route_drop_no_conn_total 51424
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 114651
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 22748
telemt_me_refill_failed_total 1453
telemt_me_writer_restored_same_endpoint_total 21114
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1619
telemt_user_connections_total{user="hello"} 131149
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 1359492144 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 39751017855 (37.02 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 79502.4 (22h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167125
telemt_connections_bad_total 1862
telemt_handshake_timeouts_total 2700
telemt_upstream_connect_attempt_total 21934
telemt_upstream_connect_success_total 21932
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 21934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11818
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 465
telemt_me_reconnect_attempts_total 19075
telemt_me_reconnect_success_total 17907
telemt_me_reader_eof_total 19194
telemt_me_idle_close_by_peer_total 19194
telemt_me_route_drop_no_conn_total 64886
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 156326
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 18103
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 17887
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 196
telemt_user_connections_total{user="hello"} 156254
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 2918764820 (2.72 GB)
telemt_user_octets_to_client{user="hello"} 71245697660 (66.35 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 79477.9 (22h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 241326
telemt_connections_bad_total 13565
telemt_handshake_timeouts_total 1804
telemt_upstream_connect_attempt_total 34094
telemt_upstream_connect_success_total 24190
telemt_upstream_connect_fail_total 9904
telemt_upstream_connect_attempts_per_request{bucket="1"} 34094
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12189
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11825
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 168
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9904
telemt_me_keepalive_timeout_total 3317
telemt_me_reconnect_attempts_total 68878
telemt_me_reconnect_success_total 17347
telemt_me_reader_eof_total 19488
telemt_me_idle_close_by_peer_total 19481
telemt_me_route_drop_no_conn_total 88128
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 202460
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 576
telemt_desync_full_logged_total 165
telemt_desync_suppressed_total 411
telemt_desync_frames_bucket_total{bucket="1_2"} 143
telemt_desync_frames_bucket_total{bucket="3_10"} 217
telemt_desync_frames_bucket_total{bucket="gt_10"} 216
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 19181
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 17337
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1834
telemt_user_connections_total{user="hello"} 205203
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 3301279518 (3.07 GB)
telemt_user_octets_to_client{user="hello"} 81470876073 (75.88 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 29649.5 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31641
telemt_connections_bad_total 5568
telemt_handshake_timeouts_total 136
telemt_upstream_connect_attempt_total 9876
telemt_upstream_connect_success_total 9782
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 9875
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4258
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5489
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 239
telemt_me_reconnect_attempts_total 9266
telemt_me_reconnect_success_total 8306
telemt_me_reader_eof_total 8872
telemt_me_idle_close_by_peer_total 8872
telemt_me_route_drop_no_conn_total 8944
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 25092
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 8413
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 8288
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 25092
telemt_user_connections_current{user="hello"} 48
telemt_user_octets_from_client{user="hello"} 200037292 (190.77 MB)
telemt_user_octets_to_client{user="hello"} 9449514400 (8.80 GB)
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 79434.5 (22h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 407563
telemt_connections_bad_total 7862
telemt_handshake_timeouts_total 3059
telemt_upstream_connect_attempt_total 16939
telemt_upstream_connect_success_total 16845
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 16939
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7846
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8974
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 1451
telemt_me_reconnect_attempts_total 16512
telemt_me_reconnect_success_total 12881
telemt_me_reader_eof_total 13837
telemt_me_idle_close_by_peer_total 13834
telemt_me_route_drop_no_conn_total 181123
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 395662
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 342
telemt_desync_full_logged_total 131
telemt_desync_suppressed_total 211
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 124
telemt_desync_frames_bucket_total{bucket="gt_10"} 137
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 13158
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 12874
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 277
telemt_user_connections_total{user="hello"} 383909
telemt_user_connections_current{user="hello"} 334
telemt_user_octets_from_client{user="hello"} 6335493720 (5.90 GB)
telemt_user_octets_to_client{user="hello"} 225444577484 (209.96 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 54
```