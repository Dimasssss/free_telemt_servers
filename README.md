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

# Server Metrics 2026-03-16 06:42:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 116894.9 (32h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 529008
telemt_connections_bad_total 5687
telemt_handshake_timeouts_total 18816
telemt_upstream_connect_attempt_total 27571
telemt_upstream_connect_success_total 27442
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 27571
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12171
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15224
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 25103
telemt_me_reconnect_success_total 21672
telemt_me_reader_eof_total 23189
telemt_me_idle_close_by_peer_total 23189
telemt_me_route_drop_no_conn_total 517032
telemt_me_route_drop_channel_closed_total 83
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 527613
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2571
telemt_desync_full_logged_total 1027
telemt_desync_suppressed_total 1544
telemt_desync_frames_bucket_total{bucket="1_2"} 518
telemt_desync_frames_bucket_total{bucket="3_10"} 1000
telemt_desync_frames_bucket_total{bucket="gt_10"} 1053
telemt_pool_swap_total 113
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22017
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 21638
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 345
telemt_user_connections_total{user="hello"} 466459
telemt_user_connections_current{user="hello"} 449
telemt_user_octets_from_client{user="hello"} 9237098240 (8.60 GB)
telemt_user_octets_to_client{user="hello"} 310938374620 (289.58 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 116902.1 (32h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 208273
telemt_connections_bad_total 3124
telemt_handshake_timeouts_total 14935
telemt_upstream_connect_attempt_total 31439
telemt_upstream_connect_success_total 31364
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 31439
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17137
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 610
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 32091
telemt_me_reconnect_success_total 25174
telemt_me_reader_eof_total 26986
telemt_me_idle_close_by_peer_total 26985
telemt_me_route_drop_no_conn_total 103737
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 182677
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 72
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 25734
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 25158
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 560
telemt_user_connections_total{user="hello"} 182211
telemt_user_connections_current{user="hello"} 242
telemt_user_octets_from_client{user="hello"} 4022253601 (3.75 GB)
telemt_user_octets_to_client{user="hello"} 96168328176 (89.56 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 116894.7 (32h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 228960
telemt_connections_bad_total 5701
telemt_handshake_timeouts_total 4571
telemt_upstream_connect_attempt_total 32695
telemt_upstream_connect_success_total 32687
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 32695
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18457
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 34247
telemt_me_reconnect_success_total 26850
telemt_me_reader_eof_total 28907
telemt_me_idle_close_by_peer_total 28906
telemt_me_route_drop_no_conn_total 80332
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 181113
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 78
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 27340
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 26842
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 490
telemt_user_connections_total{user="hello"} 180829
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 17245673697 (16.06 GB)
telemt_user_octets_to_client{user="hello"} 108548374808 (101.09 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 116894.3 (32h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 304981
telemt_connections_bad_total 1316
telemt_handshake_timeouts_total 2830
telemt_upstream_connect_attempt_total 27173
telemt_upstream_connect_success_total 27144
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 27173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14005
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 21497
telemt_me_reconnect_success_total 21365
telemt_me_reader_eof_total 22818
telemt_me_idle_close_by_peer_total 22817
telemt_me_route_drop_no_conn_total 109263
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 280364
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 980
telemt_desync_full_logged_total 343
telemt_desync_suppressed_total 637
telemt_desync_frames_bucket_total{bucket="1_2"} 198
telemt_desync_frames_bucket_total{bucket="3_10"} 422
telemt_desync_frames_bucket_total{bucket="gt_10"} 360
telemt_pool_swap_total 114
telemt_me_writer_removed_unexpected_total 21635
telemt_me_writer_restored_same_endpoint_total 21354
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 270
telemt_user_connections_total{user="hello"} 280250
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 4660219440 (4.34 GB)
telemt_user_octets_to_client{user="hello"} 122460427772 (114.05 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 91965.6 (25h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205168
telemt_connections_bad_total 35231
telemt_handshake_timeouts_total 3594
telemt_upstream_connect_attempt_total 26273
telemt_upstream_connect_success_total 26130
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 26273
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14400
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 139
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 115864
telemt_me_reconnect_success_total 21378
telemt_me_reader_eof_total 22713
telemt_me_idle_close_by_peer_total 22713
telemt_me_route_drop_no_conn_total 64503
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161031
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 445
telemt_desync_full_logged_total 106
telemt_desync_suppressed_total 339
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 176
telemt_desync_frames_bucket_total{bucket="gt_10"} 211
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 21551
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 21274
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 160662
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 2154462389 (2.01 GB)
telemt_user_octets_to_client{user="hello"} 69654693339 (64.87 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 116893.4 (32h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 756572
telemt_connections_bad_total 65007
telemt_handshake_timeouts_total 5636
telemt_upstream_connect_attempt_total 24636
telemt_upstream_connect_success_total 24504
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 24636
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11699
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12763
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 20043
telemt_me_reconnect_success_total 18700
telemt_me_reader_eof_total 19972
telemt_me_idle_close_by_peer_total 19972
telemt_me_route_drop_no_conn_total 624353
telemt_me_route_drop_channel_closed_total 101
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 763501
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
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 18961
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 18673
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 261
telemt_user_connections_total{user="hello"} 622152
telemt_user_connections_current{user="hello"} 406
telemt_user_octets_from_client{user="hello"} 13927344776 (12.97 GB)
telemt_user_octets_to_client{user="hello"} 377437454896 (351.52 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 77
```