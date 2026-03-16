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

# Server Metrics 2026-03-16 06:47:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 117200.7 (32h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 530848
telemt_connections_bad_total 5690
telemt_handshake_timeouts_total 18827
telemt_upstream_connect_attempt_total 27660
telemt_upstream_connect_success_total 27530
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 27660
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12220
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15263
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 25148
telemt_me_reconnect_success_total 21717
telemt_me_reader_eof_total 23239
telemt_me_idle_close_by_peer_total 23239
telemt_me_route_drop_no_conn_total 517423
telemt_me_route_drop_channel_closed_total 83
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 529395
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2578
telemt_desync_full_logged_total 1029
telemt_desync_suppressed_total 1549
telemt_desync_frames_bucket_total{bucket="1_2"} 518
telemt_desync_frames_bucket_total{bucket="3_10"} 1000
telemt_desync_frames_bucket_total{bucket="gt_10"} 1060
telemt_pool_swap_total 114
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22062
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 21683
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 345
telemt_user_connections_total{user="hello"} 468240
telemt_user_connections_current{user="hello"} 458
telemt_user_octets_from_client{user="hello"} 9253536916 (8.62 GB)
telemt_user_octets_to_client{user="hello"} 311860799664 (290.44 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 117208.2 (32h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 209299
telemt_connections_bad_total 3125
telemt_handshake_timeouts_total 14956
telemt_upstream_connect_attempt_total 31535
telemt_upstream_connect_success_total 31460
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 31535
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13661
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 611
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 32144
telemt_me_reconnect_success_total 25227
telemt_me_reader_eof_total 27047
telemt_me_idle_close_by_peer_total 27046
telemt_me_route_drop_no_conn_total 104109
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 183657
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 79
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 55
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 25787
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 25211
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 560
telemt_user_connections_total{user="hello"} 183189
telemt_user_connections_current{user="hello"} 273
telemt_user_octets_from_client{user="hello"} 4040497449 (3.76 GB)
telemt_user_octets_to_client{user="hello"} 97409419200 (90.72 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 117200.8 (32h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 229728
telemt_connections_bad_total 5716
telemt_handshake_timeouts_total 4580
telemt_upstream_connect_attempt_total 32795
telemt_upstream_connect_success_total 32787
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 32795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18505
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 34304
telemt_me_reconnect_success_total 26906
telemt_me_reader_eof_total 28973
telemt_me_idle_close_by_peer_total 28972
telemt_me_route_drop_no_conn_total 80546
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 181818
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
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 27397
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 26898
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 491
telemt_user_connections_total{user="hello"} 181534
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 17252649385 (16.07 GB)
telemt_user_octets_to_client{user="hello"} 108768222432 (101.30 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 117200.2 (32h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 306516
telemt_connections_bad_total 1318
telemt_handshake_timeouts_total 2834
telemt_upstream_connect_attempt_total 27262
telemt_upstream_connect_success_total 27233
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 27262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13041
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14048
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 21543
telemt_me_reconnect_success_total 21411
telemt_me_reader_eof_total 22872
telemt_me_idle_close_by_peer_total 22871
telemt_me_route_drop_no_conn_total 109716
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 281817
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 985
telemt_desync_full_logged_total 344
telemt_desync_suppressed_total 641
telemt_desync_frames_bucket_total{bucket="1_2"} 198
telemt_desync_frames_bucket_total{bucket="3_10"} 426
telemt_desync_frames_bucket_total{bucket="gt_10"} 361
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 21682
telemt_me_writer_restored_same_endpoint_total 21400
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 271
telemt_user_connections_total{user="hello"} 281704
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 4671365732 (4.35 GB)
telemt_user_octets_to_client{user="hello"} 123035609176 (114.59 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 92271.5 (25h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 206249
telemt_connections_bad_total 35287
telemt_handshake_timeouts_total 3594
telemt_upstream_connect_attempt_total 26343
telemt_upstream_connect_success_total 26200
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 26343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11623
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14438
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 139
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 115934
telemt_me_reconnect_success_total 21446
telemt_me_reader_eof_total 22786
telemt_me_idle_close_by_peer_total 22786
telemt_me_route_drop_no_conn_total 64749
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162029
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 450
telemt_desync_full_logged_total 109
telemt_desync_suppressed_total 341
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 181
telemt_desync_frames_bucket_total{bucket="gt_10"} 211
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 21619
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 21342
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 161660
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 2160658237 (2.01 GB)
telemt_user_octets_to_client{user="hello"} 69973533507 (65.17 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 117199.3 (32h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 759435
telemt_connections_bad_total 65288
telemt_handshake_timeouts_total 5690
telemt_upstream_connect_attempt_total 24717
telemt_upstream_connect_success_total 24585
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 24717
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12802
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 20080
telemt_me_reconnect_success_total 18738
telemt_me_reader_eof_total 20014
telemt_me_idle_close_by_peer_total 20014
telemt_me_route_drop_no_conn_total 625175
telemt_me_route_drop_channel_closed_total 101
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 765984
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
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 18999
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 18711
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 261
telemt_user_connections_total{user="hello"} 624634
telemt_user_connections_current{user="hello"} 504
telemt_user_octets_from_client{user="hello"} 13945737284 (12.99 GB)
telemt_user_octets_to_client{user="hello"} 378756243700 (352.74 GB)
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 84
```