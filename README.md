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

# Server Metrics 2026-03-16 05:46:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 113525.5 (31h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 490005
telemt_connections_bad_total 5502
telemt_handshake_timeouts_total 17779
telemt_upstream_connect_attempt_total 27002
telemt_upstream_connect_success_total 26878
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 27002
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14916
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 24668
telemt_me_reconnect_success_total 21238
telemt_me_reader_eof_total 22717
telemt_me_idle_close_by_peer_total 22717
telemt_me_route_drop_no_conn_total 510601
telemt_me_route_drop_channel_closed_total 82
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 507572
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2481
telemt_desync_full_logged_total 990
telemt_desync_suppressed_total 1491
telemt_desync_frames_bucket_total{bucket="1_2"} 503
telemt_desync_frames_bucket_total{bucket="3_10"} 972
telemt_desync_frames_bucket_total{bucket="gt_10"} 1006
telemt_pool_swap_total 110
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21574
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 21204
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 336
telemt_user_connections_total{user="hello"} 446419
telemt_user_connections_current{user="hello"} 371
telemt_user_octets_from_client{user="hello"} 8930087820 (8.32 GB)
telemt_user_octets_to_client{user="hello"} 304174472120 (283.28 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 113531.8 (31h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197609
telemt_connections_bad_total 3001
telemt_handshake_timeouts_total 14837
telemt_upstream_connect_attempt_total 30691
telemt_upstream_connect_success_total 30616
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 30691
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16678
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 609
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 31474
telemt_me_reconnect_success_total 24561
telemt_me_reader_eof_total 26331
telemt_me_idle_close_by_peer_total 26330
telemt_me_route_drop_no_conn_total 99831
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 172515
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 37
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 25117
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 24545
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 556
telemt_user_connections_total{user="hello"} 172058
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 3863514177 (3.60 GB)
telemt_user_octets_to_client{user="hello"} 89464975156 (83.32 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 113524.4 (31h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218184
telemt_connections_bad_total 3851
telemt_handshake_timeouts_total 4182
telemt_upstream_connect_attempt_total 31854
telemt_upstream_connect_success_total 31846
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 31854
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13786
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18007
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 33539
telemt_me_reconnect_success_total 26145
telemt_me_reader_eof_total 28159
telemt_me_idle_close_by_peer_total 28158
telemt_me_route_drop_no_conn_total 77367
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 172867
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
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 26631
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 26137
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 486
telemt_user_connections_total{user="hello"} 172591
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 16609775321 (15.47 GB)
telemt_user_octets_to_client{user="hello"} 105837211608 (98.57 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 113524.1 (31h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 289523
telemt_connections_bad_total 1280
telemt_handshake_timeouts_total 2656
telemt_upstream_connect_attempt_total 26440
telemt_upstream_connect_success_total 26414
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 26440
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13618
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 128
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 20898
telemt_me_reconnect_success_total 20772
telemt_me_reader_eof_total 22186
telemt_me_idle_close_by_peer_total 22185
telemt_me_route_drop_no_conn_total 105369
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 265958
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 931
telemt_desync_full_logged_total 326
telemt_desync_suppressed_total 605
telemt_desync_frames_bucket_total{bucket="1_2"} 184
telemt_desync_frames_bucket_total{bucket="3_10"} 402
telemt_desync_frames_bucket_total{bucket="gt_10"} 345
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 21031
telemt_me_writer_restored_same_endpoint_total 20761
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 265849
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 4479956172 (4.17 GB)
telemt_user_octets_to_client{user="hello"} 117271359776 (109.22 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 88595.5 (24h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194957
telemt_connections_bad_total 34579
telemt_handshake_timeouts_total 3446
telemt_upstream_connect_attempt_total 25366
telemt_upstream_connect_success_total 25227
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 25366
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13875
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 115133
telemt_me_reconnect_success_total 20655
telemt_me_reader_eof_total 21944
telemt_me_idle_close_by_peer_total 21944
telemt_me_route_drop_no_conn_total 61491
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 152094
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 359
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 272
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 135
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 20820
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 20551
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 151727
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 2053702357 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 66943990039 (62.35 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 113523.4 (31h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 732629
telemt_connections_bad_total 64387
telemt_handshake_timeouts_total 5485
telemt_upstream_connect_attempt_total 24044
telemt_upstream_connect_success_total 23916
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 24044
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11426
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12448
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 19585
telemt_me_reconnect_success_total 18247
telemt_me_reader_eof_total 19485
telemt_me_idle_close_by_peer_total 19485
telemt_me_route_drop_no_conn_total 614108
telemt_me_route_drop_channel_closed_total 99
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 741100
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
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 18500
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 18220
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 253
telemt_user_connections_total{user="hello"} 599766
telemt_user_connections_current{user="hello"} 450
telemt_user_octets_from_client{user="hello"} 13614274324 (12.68 GB)
telemt_user_octets_to_client{user="hello"} 368562616624 (343.25 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 53
```