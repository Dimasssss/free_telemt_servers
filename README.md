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

# Server Metrics 2026-03-15 16:20:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 65135.8 (18h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 298803
telemt_connections_bad_total 2789
telemt_handshake_timeouts_total 9010
telemt_upstream_connect_attempt_total 16144
telemt_upstream_connect_success_total 16061
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 16144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8933
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 16181
telemt_me_reconnect_success_total 12793
telemt_me_reader_eof_total 13631
telemt_me_idle_close_by_peer_total 13631
telemt_me_route_drop_no_conn_total 451642
telemt_me_route_drop_channel_closed_total 73
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 336253
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1771
telemt_desync_full_logged_total 709
telemt_desync_suppressed_total 1062
telemt_desync_frames_bucket_total{bucket="1_2"} 321
telemt_desync_frames_bucket_total{bucket="3_10"} 699
telemt_desync_frames_bucket_total{bucket="gt_10"} 751
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 13034
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 12759
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 275356
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 5836785032 (5.44 GB)
telemt_user_octets_to_client{user="hello"} 226970459600 (211.38 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 65142.6 (18h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116213
telemt_connections_bad_total 2817
telemt_handshake_timeouts_total 10957
telemt_upstream_connect_attempt_total 17973
telemt_upstream_connect_success_total 17973
telemt_upstream_connect_attempts_per_request{bucket="1"} 17973
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7751
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10020
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 202
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 17020
telemt_me_reconnect_success_total 14658
telemt_me_reader_eof_total 15651
telemt_me_idle_close_by_peer_total 15651
telemt_me_route_drop_no_conn_total 47734
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 99007
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2
telemt_desync_full_logged_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 14906
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 14642
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 248
telemt_user_connections_total{user="hello"} 98991
telemt_user_connections_current{user="hello"} 242
telemt_user_octets_from_client{user="hello"} 1898062752 (1.77 GB)
telemt_user_octets_to_client{user="hello"} 49357417352 (45.97 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 65135.2 (18h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122051
telemt_connections_bad_total 1664
telemt_handshake_timeouts_total 3058
telemt_upstream_connect_attempt_total 19480
telemt_upstream_connect_success_total 19472
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 19480
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 23500
telemt_me_reconnect_success_total 16147
telemt_me_reader_eof_total 17327
telemt_me_idle_close_by_peer_total 17327
telemt_me_route_drop_no_conn_total 47407
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 106263
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 56
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 16526
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 16139
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 379
telemt_user_connections_total{user="hello"} 106160
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 10422362184 (9.71 GB)
telemt_user_octets_to_client{user="hello"} 60910216672 (56.73 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 65134.7 (18h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163416
telemt_connections_bad_total 915
telemt_handshake_timeouts_total 996
telemt_upstream_connect_attempt_total 15679
telemt_upstream_connect_success_total 15670
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 15679
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7536
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8073
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 12480
telemt_me_reconnect_success_total 12402
telemt_me_reader_eof_total 13196
telemt_me_idle_close_by_peer_total 13196
telemt_me_route_drop_no_conn_total 63928
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 150419
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 528
telemt_desync_full_logged_total 183
telemt_desync_suppressed_total 345
telemt_desync_frames_bucket_total{bucket="1_2"} 112
telemt_desync_frames_bucket_total{bucket="3_10"} 242
telemt_desync_frames_bucket_total{bucket="gt_10"} 174
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 12550
telemt_me_writer_restored_same_endpoint_total 12391
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 150332
telemt_user_connections_current{user="hello"} 304
telemt_user_octets_from_client{user="hello"} 2839704728 (2.64 GB)
telemt_user_octets_to_client{user="hello"} 70143537008 (65.33 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 40206.4 (11h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98737
telemt_connections_bad_total 22639
telemt_handshake_timeouts_total 2195
telemt_upstream_connect_attempt_total 12538
telemt_upstream_connect_success_total 12466
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 12538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5708
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6698
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 104707
telemt_me_reconnect_success_total 10268
telemt_me_reader_eof_total 10752
telemt_me_idle_close_by_peer_total 10752
telemt_me_route_drop_no_conn_total 33869
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71491
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 162
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 124
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 67
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 10317
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 10164
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 71626
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 1113888129 (1.04 GB)
telemt_user_octets_to_client{user="hello"} 29100652947 (27.10 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 65135.0 (18h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 416389
telemt_connections_bad_total 52323
telemt_handshake_timeouts_total 3485
telemt_upstream_connect_attempt_total 14137
telemt_upstream_connect_success_total 14055
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 14137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7126
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 12058
telemt_me_reconnect_success_total 10758
telemt_me_reader_eof_total 11436
telemt_me_idle_close_by_peer_total 11436
telemt_me_route_drop_no_conn_total 243227
telemt_me_route_drop_channel_closed_total 58
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 370603
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
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 10906
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 10731
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 345383
telemt_user_connections_current{user="hello"} 691
telemt_user_octets_from_client{user="hello"} 9231877880 (8.60 GB)
telemt_user_octets_to_client{user="hello"} 182050143036 (169.55 GB)
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 87
```