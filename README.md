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

# Server Metrics 2026-03-13 07:07:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 84870.2 (23h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 323566
telemt_connections_bad_total 3141
telemt_handshake_timeouts_total 6848
telemt_upstream_connect_attempt_total 21359
telemt_upstream_connect_success_total 21261
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 21359
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11639
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1640
telemt_me_reconnect_attempts_total 20492
telemt_me_reconnect_success_total 16989
telemt_me_reader_eof_total 18170
telemt_me_idle_close_by_peer_total 18169
telemt_me_route_drop_no_conn_total 101940
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 274702
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 929
telemt_desync_full_logged_total 345
telemt_desync_suppressed_total 584
telemt_desync_frames_bucket_total{bucket="1_2"} 187
telemt_desync_frames_bucket_total{bucket="3_10"} 336
telemt_desync_frames_bucket_total{bucket="gt_10"} 406
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 17280
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 16973
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 291
telemt_user_connections_total{user="hello"} 274402
telemt_user_connections_current{user="hello"} 345
telemt_user_octets_from_client{user="hello"} 4613492636 (4.30 GB)
telemt_user_octets_to_client{user="hello"} 129797179144 (120.88 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 84763.2 (23h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147905
telemt_connections_bad_total 1422
telemt_handshake_timeouts_total 1144
telemt_upstream_connect_attempt_total 44014
telemt_upstream_connect_success_total 43432
telemt_upstream_connect_fail_total 582
telemt_upstream_connect_attempts_per_request{bucket="1"} 44014
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25515
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17407
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 510
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 582
telemt_me_keepalive_timeout_total 652
telemt_me_reconnect_attempts_total 72290
telemt_me_reconnect_success_total 22680
telemt_me_reader_eof_total 24911
telemt_me_idle_close_by_peer_total 24911
telemt_me_route_drop_no_conn_total 55837
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 123499
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 17
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
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 24410
telemt_me_refill_failed_total 1548
telemt_me_writer_restored_same_endpoint_total 22665
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1730
telemt_user_connections_total{user="hello"} 139993
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 1444282268 (1.35 GB)
telemt_user_octets_to_client{user="hello"} 45341572759 (42.23 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 84726.7 (23h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179421
telemt_connections_bad_total 1912
telemt_handshake_timeouts_total 2912
telemt_upstream_connect_attempt_total 23112
telemt_upstream_connect_success_total 23110
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 23112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10654
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12433
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 555
telemt_me_reconnect_attempts_total 19992
telemt_me_reconnect_success_total 18818
telemt_me_reader_eof_total 20170
telemt_me_idle_close_by_peer_total 20170
telemt_me_route_drop_no_conn_total 69247
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167924
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
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 19020
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 18798
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 167852
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 2996691292 (2.79 GB)
telemt_user_octets_to_client{user="hello"} 73871434500 (68.80 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 84702.3 (23h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 257655
telemt_connections_bad_total 13612
telemt_handshake_timeouts_total 1964
telemt_upstream_connect_attempt_total 35788
telemt_upstream_connect_success_total 25842
telemt_upstream_connect_fail_total 9945
telemt_upstream_connect_attempts_per_request{bucket="1"} 35787
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12707
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 176
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9945
telemt_me_keepalive_timeout_total 3356
telemt_me_reconnect_attempts_total 70277
telemt_me_reconnect_success_total 18737
telemt_me_reader_eof_total 20925
telemt_me_idle_close_by_peer_total 20918
telemt_me_route_drop_no_conn_total 93227
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 217638
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 683
telemt_desync_full_logged_total 197
telemt_desync_suppressed_total 486
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 257
telemt_desync_frames_bucket_total{bucket="gt_10"} 259
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 20591
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 18727
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1854
telemt_user_connections_total{user="hello"} 220371
telemt_user_connections_current{user="hello"} 225
telemt_user_octets_from_client{user="hello"} 4609404974 (4.29 GB)
telemt_user_octets_to_client{user="hello"} 84922510233 (79.09 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 34873.9 (9h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41721
telemt_connections_bad_total 7203
telemt_handshake_timeouts_total 376
telemt_upstream_connect_attempt_total 11882
telemt_upstream_connect_success_total 11764
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 11882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6618
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 283
telemt_me_reconnect_attempts_total 10987
telemt_me_reconnect_success_total 10019
telemt_me_reader_eof_total 10690
telemt_me_idle_close_by_peer_total 10690
telemt_me_route_drop_no_conn_total 11810
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33094
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 10140
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 10001
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 33094
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 243633180 (232.35 MB)
telemt_user_octets_to_client{user="hello"} 10591773152 (9.86 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 84658.8 (23h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 436959
telemt_connections_bad_total 8907
telemt_handshake_timeouts_total 3293
telemt_upstream_connect_attempt_total 18010
telemt_upstream_connect_success_total 17913
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 18010
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9534
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_timeout_total 1494
telemt_me_reconnect_attempts_total 17341
telemt_me_reconnect_success_total 13704
telemt_me_reader_eof_total 14717
telemt_me_idle_close_by_peer_total 14714
telemt_me_route_drop_no_conn_total 192878
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 421721
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 362
telemt_desync_full_logged_total 139
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 13991
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 13697
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 409952
telemt_user_connections_current{user="hello"} 409
telemt_user_octets_from_client{user="hello"} 6629510080 (6.17 GB)
telemt_user_octets_to_client{user="hello"} 236913541264 (220.64 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 68
```