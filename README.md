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

# Server Metrics 2026-03-15 14:32:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 58705.6 (16h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 264593
telemt_connections_bad_total 2449
telemt_handshake_timeouts_total 6469
telemt_upstream_connect_attempt_total 14836
telemt_upstream_connect_success_total 14759
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 14836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8204
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 15182
telemt_me_reconnect_success_total 11802
telemt_me_reader_eof_total 12587
telemt_me_idle_close_by_peer_total 12587
telemt_me_route_drop_no_conn_total 439772
telemt_me_route_drop_channel_closed_total 72
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 306318
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1703
telemt_desync_full_logged_total 677
telemt_desync_suppressed_total 1026
telemt_desync_frames_bucket_total{bucket="1_2"} 305
telemt_desync_frames_bucket_total{bucket="3_10"} 664
telemt_desync_frames_bucket_total{bucket="gt_10"} 734
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 12027
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 11771
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 225
telemt_user_connections_total{user="hello"} 245424
telemt_user_connections_current{user="hello"} 410
telemt_user_octets_from_client{user="hello"} 5393075424 (5.02 GB)
telemt_user_octets_to_client{user="hello"} 213343314608 (198.69 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 58712.2 (16h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98101
telemt_connections_bad_total 2782
telemt_handshake_timeouts_total 9556
telemt_upstream_connect_attempt_total 16190
telemt_upstream_connect_success_total 16190
telemt_upstream_connect_attempts_per_request{bucket="1"} 16190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6961
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9079
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 15550
telemt_me_reconnect_success_total 13199
telemt_me_reader_eof_total 14117
telemt_me_idle_close_by_peer_total 14117
telemt_me_route_drop_no_conn_total 41621
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 82741
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 13427
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 13183
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 228
telemt_user_connections_total{user="hello"} 82732
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 1623417212 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 39757630636 (37.03 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 58704.8 (16h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107027
telemt_connections_bad_total 1649
telemt_handshake_timeouts_total 2789
telemt_upstream_connect_attempt_total 17428
telemt_upstream_connect_success_total 17420
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 17428
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9868
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 21249
telemt_me_reconnect_success_total 14421
telemt_me_reader_eof_total 15485
telemt_me_idle_close_by_peer_total 15485
telemt_me_route_drop_no_conn_total 40044
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92056
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 55
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 14767
telemt_me_refill_failed_total 211
telemt_me_writer_restored_same_endpoint_total 14413
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 346
telemt_user_connections_total{user="hello"} 91958
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 10158504888 (9.46 GB)
telemt_user_octets_to_client{user="hello"} 53892597964 (50.19 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 58704.2 (16h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140914
telemt_connections_bad_total 790
telemt_handshake_timeouts_total 919
telemt_upstream_connect_attempt_total 14041
telemt_upstream_connect_success_total 14037
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 14041
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6749
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7237
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 11147
telemt_me_reconnect_success_total 11077
telemt_me_reader_eof_total 11783
telemt_me_idle_close_by_peer_total 11783
telemt_me_route_drop_no_conn_total 54878
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128736
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 452
telemt_desync_full_logged_total 142
telemt_desync_suppressed_total 310
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 204
telemt_desync_frames_bucket_total{bucket="gt_10"} 153
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 11206
telemt_me_writer_restored_same_endpoint_total 11066
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 128652
telemt_user_connections_current{user="hello"} 264
telemt_user_octets_from_client{user="hello"} 2443426620 (2.28 GB)
telemt_user_octets_to_client{user="hello"} 63616136496 (59.25 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 33775.7 (9h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81391
telemt_connections_bad_total 21342
telemt_handshake_timeouts_total 1424
telemt_upstream_connect_attempt_total 10680
telemt_upstream_connect_success_total 10613
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 10680
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5741
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 103161
telemt_me_reconnect_success_total 8732
telemt_me_reader_eof_total 9134
telemt_me_idle_close_by_peer_total 9134
telemt_me_route_drop_no_conn_total 27540
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56765
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 155
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 65
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 8749
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 8628
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 56902
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 844875969 (805.74 MB)
telemt_user_octets_to_client{user="hello"} 23027241883 (21.45 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 58704.4 (16h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 354158
telemt_connections_bad_total 48461
telemt_handshake_timeouts_total 2915
telemt_upstream_connect_attempt_total 12655
telemt_upstream_connect_success_total 12579
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 12655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6314
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 10890
telemt_me_reconnect_success_total 9603
telemt_me_reader_eof_total 10235
telemt_me_idle_close_by_peer_total 10235
telemt_me_route_drop_no_conn_total 164029
telemt_me_route_drop_channel_closed_total 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 292238
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 301
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 222
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 9733
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 9576
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 290094
telemt_user_connections_current{user="hello"} 576
telemt_user_octets_from_client{user="hello"} 7190286264 (6.70 GB)
telemt_user_octets_to_client{user="hello"} 144811548064 (134.87 GB)
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 59
```