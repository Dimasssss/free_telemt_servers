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

# Server Metrics 2026-03-17 08:31:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 49585.7 (13h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 355467
telemt_connections_bad_total 3586
telemt_handshake_timeouts_total 10423
telemt_upstream_connect_attempt_total 10219
telemt_upstream_connect_success_total 10150
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 10218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4684
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5452
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 8890
telemt_me_reconnect_success_total 7690
telemt_me_reader_eof_total 8195
telemt_me_idle_close_by_peer_total 8195
telemt_me_route_drop_no_conn_total 109427
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 321967
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2507
telemt_desync_full_logged_total 709
telemt_desync_suppressed_total 1798
telemt_desync_frames_bucket_total{bucket="1_2"} 579
telemt_desync_frames_bucket_total{bucket="3_10"} 1196
telemt_desync_frames_bucket_total{bucket="gt_10"} 732
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 7826
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 7669
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 321699
telemt_user_connections_current{user="hello"} 920
telemt_user_octets_from_client{user="hello"} 4610723404 (4.29 GB)
telemt_user_octets_to_client{user="hello"} 132743693188 (123.63 GB)
telemt_user_unique_ips_current{user="hello"} 311
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 49837.7 (13h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197871
telemt_connections_bad_total 2369
telemt_handshake_timeouts_total 12258
telemt_upstream_connect_attempt_total 13556
telemt_upstream_connect_success_total 13377
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 13556
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5715
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7544
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 118
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_reconnect_attempts_total 13173
telemt_me_reconnect_success_total 10900
telemt_me_reader_eof_total 11529
telemt_me_idle_close_by_peer_total 11529
telemt_me_route_drop_no_conn_total 71953
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 173333
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 440
telemt_desync_full_logged_total 162
telemt_desync_suppressed_total 278
telemt_desync_frames_bucket_total{bucket="1_2"} 134
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 118
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 11080
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 10884
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 173345
telemt_user_connections_current{user="hello"} 500
telemt_user_octets_from_client{user="hello"} 2102133892 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 68711040680 (63.99 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 49613.4 (13h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122086
telemt_connections_bad_total 7518
telemt_handshake_timeouts_total 6453
telemt_upstream_connect_attempt_total 13113
telemt_upstream_connect_success_total 13043
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 13113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5773
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7208
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 10592
telemt_me_reconnect_success_total 10527
telemt_me_reader_eof_total 11241
telemt_me_idle_close_by_peer_total 11241
telemt_me_route_drop_no_conn_total 38023
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 99188
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 255
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 193
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 10662
telemt_me_writer_restored_same_endpoint_total 10516
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 99130
telemt_user_connections_current{user="hello"} 233
telemt_user_octets_from_client{user="hello"} 6578578564 (6.13 GB)
telemt_user_octets_to_client{user="hello"} 31537634720 (29.37 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 49672.6 (13h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 263481
telemt_connections_bad_total 6167
telemt_handshake_timeouts_total 10456
telemt_upstream_connect_attempt_total 11370
telemt_upstream_connect_success_total 11271
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 11370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5876
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 9787
telemt_me_reconnect_success_total 8718
telemt_me_reader_eof_total 9281
telemt_me_idle_close_by_peer_total 9281
telemt_me_route_drop_no_conn_total 70926
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 205377
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 430
telemt_desync_full_logged_total 155
telemt_desync_suppressed_total 275
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 179
telemt_desync_frames_bucket_total{bucket="gt_10"} 142
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 8879
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 8710
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 205367
telemt_user_connections_current{user="hello"} 629
telemt_user_octets_from_client{user="hello"} 2213251826 (2.06 GB)
telemt_user_octets_to_client{user="hello"} 89878594913 (83.71 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 49644.5 (13h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148471
telemt_connections_bad_total 39698
telemt_handshake_timeouts_total 2644
telemt_upstream_connect_attempt_total 15288
telemt_upstream_connect_success_total 15085
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 15288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6744
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8148
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_reconnect_attempts_total 18722
telemt_me_reconnect_success_total 12479
telemt_me_reader_eof_total 13222
telemt_me_idle_close_by_peer_total 13222
telemt_me_route_drop_no_conn_total 39238
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 101406
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 278
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 211
telemt_desync_frames_bucket_total{bucket="1_2"} 128
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 12826
telemt_me_refill_failed_total 193
telemt_me_writer_restored_same_endpoint_total 12471
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 347
telemt_user_connections_total{user="hello"} 101440
telemt_user_connections_current{user="hello"} 265
telemt_user_octets_from_client{user="hello"} 1669964535 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 47725704118 (44.45 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 49806.5 (13h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 361089
telemt_connections_bad_total 46099
telemt_handshake_timeouts_total 3552
telemt_upstream_connect_attempt_total 10254
telemt_upstream_connect_success_total 10198
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 10254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4972
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5211
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 11585
telemt_me_reconnect_success_total 7708
telemt_me_reader_eof_total 8335
telemt_me_idle_close_by_peer_total 8335
telemt_me_route_drop_no_conn_total 253268
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 368859
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 462
telemt_desync_full_logged_total 187
telemt_desync_suppressed_total 275
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 170
telemt_desync_frames_bucket_total{bucket="gt_10"} 148
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 7941
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 7694
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 233
telemt_user_connections_total{user="hello"} 290770
telemt_user_connections_current{user="hello"} 795
telemt_user_octets_from_client{user="hello"} 4096565920 (3.82 GB)
telemt_user_octets_to_client{user="hello"} 171888389520 (160.08 GB)
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 37812.1 (10h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3078
telemt_connections_bad_total 207
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 18449
telemt_upstream_connect_success_total 18447
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 18449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8052
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 16601
telemt_me_reconnect_success_total 16507
telemt_me_reader_eof_total 18050
telemt_me_idle_close_by_peer_total 18050
telemt_me_route_drop_no_conn_total 553
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2816
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 16654
telemt_me_writer_restored_same_endpoint_total 16507
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 2816
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 715442084 (682.30 MB)
telemt_user_octets_to_client{user="hello"} 19217263812 (17.90 GB)
telemt_user_unique_ips_current{user="hello"} 14
telemt_user_unique_ips_recent_window{user="hello"} 5
```