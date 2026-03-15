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

# Server Metrics 2026-03-15 17:16:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 68506.5 (19h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 317629
telemt_connections_bad_total 2858
telemt_handshake_timeouts_total 9232
telemt_upstream_connect_attempt_total 16737
telemt_upstream_connect_success_total 16650
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 16737
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7378
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9242
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 16598
telemt_me_reconnect_success_total 13206
telemt_me_reader_eof_total 14064
telemt_me_idle_close_by_peer_total 14064
telemt_me_route_drop_no_conn_total 457718
telemt_me_route_drop_channel_closed_total 76
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 354061
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1807
telemt_desync_full_logged_total 720
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 333
telemt_desync_frames_bucket_total{bucket="3_10"} 714
telemt_desync_frames_bucket_total{bucket="gt_10"} 760
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 13452
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 13172
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 246
telemt_user_connections_total{user="hello"} 293161
telemt_user_connections_current{user="hello"} 408
telemt_user_octets_from_client{user="hello"} 6039533228 (5.62 GB)
telemt_user_octets_to_client{user="hello"} 235850199104 (219.65 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 68514.0 (19h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125031
telemt_connections_bad_total 2827
telemt_handshake_timeouts_total 11590
telemt_upstream_connect_attempt_total 18776
telemt_upstream_connect_success_total 18776
telemt_upstream_connect_attempts_per_request{bucket="1"} 18776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10456
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 265
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 17651
telemt_me_reconnect_success_total 15288
telemt_me_reader_eof_total 16339
telemt_me_idle_close_by_peer_total 16338
telemt_me_route_drop_no_conn_total 52786
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 106938
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 15556
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 15272
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 268
telemt_user_connections_total{user="hello"} 106921
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 2067077376 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 53403809156 (49.74 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 68505.8 (19h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130610
telemt_connections_bad_total 1693
telemt_handshake_timeouts_total 3145
telemt_upstream_connect_attempt_total 20293
telemt_upstream_connect_success_total 20285
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 20293
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8788
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11461
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 24139
telemt_me_reconnect_success_total 16783
telemt_me_reader_eof_total 18005
telemt_me_idle_close_by_peer_total 18005
telemt_me_route_drop_no_conn_total 51083
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 114358
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 59
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 17172
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 16775
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 389
telemt_user_connections_total{user="hello"} 114252
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 10623078276 (9.89 GB)
telemt_user_octets_to_client{user="hello"} 64516028796 (60.09 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 68505.5 (19h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176600
telemt_connections_bad_total 922
telemt_handshake_timeouts_total 1121
telemt_upstream_connect_attempt_total 16378
telemt_upstream_connect_success_total 16366
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 16378
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7856
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8444
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 13001
telemt_me_reconnect_success_total 12920
telemt_me_reader_eof_total 13746
telemt_me_idle_close_by_peer_total 13746
telemt_me_route_drop_no_conn_total 68393
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162794
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 561
telemt_desync_full_logged_total 202
telemt_desync_suppressed_total 359
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 261
telemt_desync_frames_bucket_total{bucket="gt_10"} 187
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 13078
telemt_me_writer_restored_same_endpoint_total 12909
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 162707
telemt_user_connections_current{user="hello"} 246
telemt_user_octets_from_client{user="hello"} 3060265164 (2.85 GB)
telemt_user_octets_to_client{user="hello"} 73484555904 (68.44 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 43576.8 (12h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107756
telemt_connections_bad_total 23252
telemt_handshake_timeouts_total 2381
telemt_upstream_connect_attempt_total 13292
telemt_upstream_connect_success_total 13216
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 13292
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7092
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 105285
telemt_me_reconnect_success_total 10844
telemt_me_reader_eof_total 11379
telemt_me_idle_close_by_peer_total 11379
telemt_me_route_drop_no_conn_total 36771
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79328
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 194
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 147
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 76
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 10903
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 10740
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 79461
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 1340780561 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 31457776175 (29.30 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 68505.9 (19h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 453769
telemt_connections_bad_total 57533
telemt_handshake_timeouts_total 3734
telemt_upstream_connect_attempt_total 14873
telemt_upstream_connect_success_total 14784
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 14873
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7566
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 12612
telemt_me_reconnect_success_total 11309
telemt_me_reader_eof_total 12014
telemt_me_idle_close_by_peer_total 12014
telemt_me_route_drop_no_conn_total 274988
telemt_me_route_drop_channel_closed_total 71
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 407182
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 317
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 231
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 11469
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 11282
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 375869
telemt_user_connections_current{user="hello"} 573
telemt_user_octets_from_client{user="hello"} 10032370724 (9.34 GB)
telemt_user_octets_to_client{user="hello"} 199685447560 (185.97 GB)
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 80
```