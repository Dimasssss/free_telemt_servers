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

# Server Metrics 2026-03-16 09:56:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 128536.7 (35h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 627026
telemt_connections_bad_total 11033
telemt_handshake_timeouts_total 22197
telemt_upstream_connect_attempt_total 30154
telemt_upstream_connect_success_total 30011
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 30154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16597
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 31032
telemt_me_reconnect_success_total 23652
telemt_me_reader_eof_total 25355
telemt_me_idle_close_by_peer_total 25355
telemt_me_route_drop_no_conn_total 586528
telemt_me_route_drop_channel_closed_total 86
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 615918
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2925
telemt_desync_full_logged_total 1124
telemt_desync_suppressed_total 1801
telemt_desync_frames_bucket_total{bucket="1_2"} 639
telemt_desync_frames_bucket_total{bucket="3_10"} 1119
telemt_desync_frames_bucket_total{bucket="gt_10"} 1167
telemt_pool_swap_total 121
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24139
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 23618
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 487
telemt_user_connections_total{user="hello"} 552478
telemt_user_connections_current{user="hello"} 503
telemt_user_octets_from_client{user="hello"} 10733200324 (10.00 GB)
telemt_user_octets_to_client{user="hello"} 341587413892 (318.13 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 128544.0 (35h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 258628
telemt_connections_bad_total 3748
telemt_handshake_timeouts_total 15561
telemt_upstream_connect_attempt_total 34442
telemt_upstream_connect_success_total 34367
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 34442
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18840
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 693
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 37908
telemt_me_reconnect_success_total 27589
telemt_me_reader_eof_total 29597
telemt_me_idle_close_by_peer_total 29596
telemt_me_route_drop_no_conn_total 122843
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 230415
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 196
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 133
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 28297
telemt_me_refill_failed_total 314
telemt_me_writer_restored_same_endpoint_total 27573
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 708
telemt_user_connections_total{user="hello"} 229950
telemt_user_connections_current{user="hello"} 287
telemt_user_octets_from_client{user="hello"} 4996289389 (4.65 GB)
telemt_user_octets_to_client{user="hello"} 124638715040 (116.08 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 128536.8 (35h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 266276
telemt_connections_bad_total 5763
telemt_handshake_timeouts_total 6134
telemt_upstream_connect_attempt_total 35835
telemt_upstream_connect_success_total 35827
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 35835
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15473
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20300
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 36808
telemt_me_reconnect_success_total 29387
telemt_me_reader_eof_total 31574
telemt_me_idle_close_by_peer_total 31573
telemt_me_route_drop_no_conn_total 91825
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 215755
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
telemt_me_writer_removed_unexpected_total 29909
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 29379
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 522
telemt_user_connections_total{user="hello"} 215455
telemt_user_connections_current{user="hello"} 238
telemt_user_octets_from_client{user="hello"} 17702306089 (16.49 GB)
telemt_user_octets_to_client{user="hello"} 119653458260 (111.44 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 128536.3 (35h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 384558
telemt_connections_bad_total 1400
telemt_handshake_timeouts_total 3481
telemt_upstream_connect_attempt_total 29737
telemt_upstream_connect_success_total 29698
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 29737
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15266
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 25681
telemt_me_reconnect_success_total 23317
telemt_me_reader_eof_total 24932
telemt_me_idle_close_by_peer_total 24931
telemt_me_route_drop_no_conn_total 133922
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 355827
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1301
telemt_desync_full_logged_total 448
telemt_desync_suppressed_total 853
telemt_desync_frames_bucket_total{bucket="1_2"} 261
telemt_desync_frames_bucket_total{bucket="3_10"} 553
telemt_desync_frames_bucket_total{bucket="gt_10"} 487
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 23700
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 23306
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 383
telemt_user_connections_total{user="hello"} 355700
telemt_user_connections_current{user="hello"} 432
telemt_user_octets_from_client{user="hello"} 5945160138 (5.54 GB)
telemt_user_octets_to_client{user="hello"} 142379498540 (132.60 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 103607.6 (28h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 241563
telemt_connections_bad_total 38166
telemt_handshake_timeouts_total 4259
telemt_upstream_connect_attempt_total 29553
telemt_upstream_connect_success_total 29391
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 29553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16219
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 118559
telemt_me_reconnect_success_total 24055
telemt_me_reader_eof_total 25543
telemt_me_idle_close_by_peer_total 25543
telemt_me_route_drop_no_conn_total 75497
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 192233
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 632
telemt_desync_full_logged_total 144
telemt_desync_suppressed_total 488
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 254
telemt_desync_frames_bucket_total{bucket="gt_10"} 281
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 24259
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 23951
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 191847
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 2501441405 (2.33 GB)
telemt_user_octets_to_client{user="hello"} 83868625251 (78.11 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 128535.8 (35h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 876725
telemt_connections_bad_total 72649
telemt_handshake_timeouts_total 10238
telemt_upstream_connect_attempt_total 26956
telemt_upstream_connect_success_total 26814
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 26956
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12725
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14047
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 23029
telemt_me_reconnect_success_total 20427
telemt_me_reader_eof_total 21827
telemt_me_idle_close_by_peer_total 21827
telemt_me_route_drop_no_conn_total 669969
telemt_me_route_drop_channel_closed_total 120
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 864761
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 369
telemt_desync_full_logged_total 105
telemt_desync_suppressed_total 264
telemt_desync_frames_bucket_total{bucket="1_2"} 173
telemt_desync_frames_bucket_total{bucket="3_10"} 108
telemt_desync_frames_bucket_total{bucket="gt_10"} 88
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 20749
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 20400
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 322
telemt_user_connections_total{user="hello"} 723398
telemt_user_connections_current{user="hello"} 692
telemt_user_octets_from_client{user="hello"} 15459983544 (14.40 GB)
telemt_user_octets_to_client{user="hello"} 434740092368 (404.88 GB)
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 107
```