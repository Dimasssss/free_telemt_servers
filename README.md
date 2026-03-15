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

# Server Metrics 2026-03-15 13:31:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 55029.8 (15h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 245857
telemt_connections_bad_total 2273
telemt_handshake_timeouts_total 5411
telemt_upstream_connect_attempt_total 13856
telemt_upstream_connect_success_total 13782
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 13856
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7634
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 14382
telemt_me_reconnect_success_total 11005
telemt_me_reader_eof_total 11754
telemt_me_idle_close_by_peer_total 11754
telemt_me_route_drop_no_conn_total 432483
telemt_me_route_drop_channel_closed_total 66
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 289899
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1659
telemt_desync_full_logged_total 657
telemt_desync_suppressed_total 1002
telemt_desync_frames_bucket_total{bucket="1_2"} 293
telemt_desync_frames_bucket_total{bucket="3_10"} 654
telemt_desync_frames_bucket_total{bucket="gt_10"} 712
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 11223
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 10974
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 229003
telemt_user_connections_current{user="hello"} 378
telemt_user_octets_from_client{user="hello"} 5013238580 (4.67 GB)
telemt_user_octets_to_client{user="hello"} 202906470056 (188.97 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 55036.0 (15h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89529
telemt_connections_bad_total 2746
telemt_handshake_timeouts_total 8166
telemt_upstream_connect_attempt_total 15168
telemt_upstream_connect_success_total 15168
telemt_upstream_connect_attempts_per_request{bucket="1"} 15168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8513
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 14707
telemt_me_reconnect_success_total 12364
telemt_me_reader_eof_total 13228
telemt_me_idle_close_by_peer_total 13228
telemt_me_route_drop_no_conn_total 38175
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75868
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 12573
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 12348
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 75865
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 1498991920 (1.40 GB)
telemt_user_octets_to_client{user="hello"} 36869592212 (34.34 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 55029.1 (15h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91849
telemt_connections_bad_total 1610
telemt_handshake_timeouts_total 2733
telemt_upstream_connect_attempt_total 16071
telemt_upstream_connect_success_total 16063
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 16071
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9060
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 15406
telemt_me_reconnect_success_total 13255
telemt_me_reader_eof_total 14165
telemt_me_idle_close_by_peer_total 14165
telemt_me_route_drop_no_conn_total 35673
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 83575
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 54
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 13448
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 13247
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 193
telemt_user_connections_total{user="hello"} 83482
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 9950920368 (9.27 GB)
telemt_user_octets_to_client{user="hello"} 51198187844 (47.68 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 55028.2 (15h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126436
telemt_connections_bad_total 551
telemt_handshake_timeouts_total 814
telemt_upstream_connect_attempt_total 12916
telemt_upstream_connect_success_total 12913
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 12916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6686
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 10198
telemt_me_reconnect_success_total 10137
telemt_me_reader_eof_total 10812
telemt_me_idle_close_by_peer_total 10812
telemt_me_route_drop_no_conn_total 49288
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 115082
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 392
telemt_desync_full_logged_total 114
telemt_desync_suppressed_total 278
telemt_desync_frames_bucket_total{bucket="1_2"} 88
telemt_desync_frames_bucket_total{bucket="3_10"} 165
telemt_desync_frames_bucket_total{bucket="gt_10"} 139
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 10253
telemt_me_writer_restored_same_endpoint_total 10126
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 114999
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 2157911244 (2.01 GB)
telemt_user_octets_to_client{user="hello"} 59925989884 (55.81 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 30099.5 (8h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73160
telemt_connections_bad_total 20686
telemt_handshake_timeouts_total 1390
telemt_upstream_connect_attempt_total 9611
telemt_upstream_connect_success_total 9547
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 9611
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5219
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_reconnect_attempts_total 102272
telemt_me_reconnect_success_total 7847
telemt_me_reader_eof_total 8199
telemt_me_idle_close_by_peer_total 8199
telemt_me_route_drop_no_conn_total 24298
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49458
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 117
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 91
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 7853
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 7743
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 49594
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 759501617 (724.32 MB)
telemt_user_octets_to_client{user="hello"} 20054000207 (18.68 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 55027.7 (15h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 324750
telemt_connections_bad_total 47899
telemt_handshake_timeouts_total 2571
telemt_upstream_connect_attempt_total 11760
telemt_upstream_connect_success_total 11689
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 11760
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5822
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_reconnect_attempts_total 8963
telemt_me_reconnect_success_total 8900
telemt_me_reader_eof_total 9465
telemt_me_idle_close_by_peer_total 9465
telemt_me_route_drop_no_conn_total 148863
telemt_me_route_drop_channel_closed_total 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 265145
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 274
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 200
telemt_desync_frames_bucket_total{bucket="1_2"} 150
telemt_desync_frames_bucket_total{bucket="3_10"} 81
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 8983
telemt_me_writer_restored_same_endpoint_total 8873
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 263026
telemt_user_connections_current{user="hello"} 559
telemt_user_octets_from_client{user="hello"} 5318600104 (4.95 GB)
telemt_user_octets_to_client{user="hello"} 128499534620 (119.67 GB)
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 55
```