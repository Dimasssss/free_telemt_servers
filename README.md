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

# Server Metrics 2026-03-14 19:16:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 21626.7 (6h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117212
telemt_connections_bad_total 15751
telemt_handshake_timeouts_total 1088
telemt_upstream_connect_attempt_total 4983
telemt_upstream_connect_success_total 4981
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4983
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 183
telemt_me_reconnect_attempts_total 3906
telemt_me_reconnect_success_total 3873
telemt_me_reader_eof_total 4100
telemt_me_idle_close_by_peer_total 4100
telemt_me_route_drop_no_conn_total 41245
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95309
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 383
telemt_desync_full_logged_total 141
telemt_desync_suppressed_total 242
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 143
telemt_desync_frames_bucket_total{bucket="gt_10"} 142
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3935
telemt_me_writer_restored_same_endpoint_total 3855
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 95237
telemt_user_connections_current{user="hello"} 302
telemt_user_octets_from_client{user="hello"} 1882257936 (1.75 GB)
telemt_user_octets_to_client{user="hello"} 47296698372 (44.05 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 21625.0 (6h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47828
telemt_connections_bad_total 661
telemt_handshake_timeouts_total 882
telemt_upstream_connect_attempt_total 5655
telemt_upstream_connect_success_total 5615
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 5654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3236
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 108
telemt_me_reconnect_attempts_total 7083
telemt_me_reconnect_success_total 4509
telemt_me_reader_eof_total 4788
telemt_me_idle_close_by_peer_total 4788
telemt_me_route_drop_no_conn_total 25202
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44526
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 4652
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 4504
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 44515
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 647208772 (617.23 MB)
telemt_user_octets_to_client{user="hello"} 18921212184 (17.62 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 21629.5 (6h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51782
telemt_connections_bad_total 385
telemt_handshake_timeouts_total 1824
telemt_upstream_connect_attempt_total 7512
telemt_upstream_connect_success_total 7433
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 7512
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3889
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 103870
telemt_me_reconnect_success_total 6008
telemt_me_reader_eof_total 6406
telemt_me_idle_close_by_peer_total 6406
telemt_me_route_drop_no_conn_total 20289
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46751
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 8
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
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 6273
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 5967
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 265
telemt_user_connections_total{user="hello"} 46815
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 3117937057 (2.90 GB)
telemt_user_octets_to_client{user="hello"} 28074448774 (26.15 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 21634.2 (6h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66076
telemt_connections_bad_total 180
telemt_handshake_timeouts_total 553
telemt_upstream_connect_attempt_total 5272
telemt_upstream_connect_success_total 5240
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 5272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2382
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2835
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 4156
telemt_me_reconnect_success_total 4133
telemt_me_reader_eof_total 4331
telemt_me_idle_close_by_peer_total 4331
telemt_me_route_drop_no_conn_total 29223
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62450
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 535
telemt_desync_full_logged_total 135
telemt_desync_suppressed_total 400
telemt_desync_frames_bucket_total{bucket="1_2"} 88
telemt_desync_frames_bucket_total{bucket="3_10"} 218
telemt_desync_frames_bucket_total{bucket="gt_10"} 229
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 4177
telemt_me_writer_restored_same_endpoint_total 4131
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 62326
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 870892144 (830.55 MB)
telemt_user_octets_to_client{user="hello"} 19677903664 (18.33 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 21627.3 (6h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49371
telemt_connections_bad_total 4175
telemt_handshake_timeouts_total 3119
telemt_upstream_connect_attempt_total 4961
telemt_upstream_connect_success_total 4904
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 4960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2683
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 125
telemt_me_reconnect_attempts_total 10323
telemt_me_reconnect_success_total 3795
telemt_me_reader_eof_total 4147
telemt_me_idle_close_by_peer_total 4147
telemt_me_route_drop_no_conn_total 16808
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 39716
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 239
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 204
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 81
telemt_desync_frames_bucket_total{bucket="gt_10"} 126
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 4036
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 3791
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 39705
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 621415352 (592.63 MB)
telemt_user_octets_to_client{user="hello"} 11913630484 (11.10 GB)
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 21627.3 (6h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 172036
telemt_connections_bad_total 7209
telemt_handshake_timeouts_total 2597
telemt_upstream_connect_attempt_total 4218
telemt_upstream_connect_success_total 4145
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 4218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2103
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 8039
telemt_me_reconnect_success_total 3039
telemt_me_reader_eof_total 3306
telemt_me_idle_close_by_peer_total 3306
telemt_me_route_drop_no_conn_total 97508
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 157195
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 42
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 27
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3228
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 3035
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 153692
telemt_user_connections_current{user="hello"} 463
telemt_user_octets_from_client{user="hello"} 3416414264 (3.18 GB)
telemt_user_octets_to_client{user="hello"} 78019367896 (72.66 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 64
```