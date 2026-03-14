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

# Server Metrics 2026-03-14 17:55:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 16721.8 (4h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95703
telemt_connections_bad_total 14307
telemt_handshake_timeouts_total 493
telemt_upstream_connect_attempt_total 3997
telemt_upstream_connect_success_total 3995
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 3997
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1914
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2008
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 114
telemt_me_reconnect_attempts_total 3138
telemt_me_reconnect_success_total 3107
telemt_me_reader_eof_total 3278
telemt_me_idle_close_by_peer_total 3278
telemt_me_route_drop_no_conn_total 34117
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77264
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 310
telemt_desync_full_logged_total 114
telemt_desync_suppressed_total 196
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 118
telemt_desync_frames_bucket_total{bucket="gt_10"} 120
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3158
telemt_me_writer_restored_same_endpoint_total 3089
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 77192
telemt_user_connections_current{user="hello"} 339
telemt_user_octets_from_client{user="hello"} 1638821512 (1.53 GB)
telemt_user_octets_to_client{user="hello"} 36275123572 (33.78 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 16720.0 (4h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38787
telemt_connections_bad_total 454
telemt_handshake_timeouts_total 829
telemt_upstream_connect_attempt_total 4597
telemt_upstream_connect_success_total 4562
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 4597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1850
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2635
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 82
telemt_me_reconnect_attempts_total 6248
telemt_me_reconnect_success_total 3675
telemt_me_reader_eof_total 3898
telemt_me_idle_close_by_peer_total 3898
telemt_me_route_drop_no_conn_total 20518
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36113
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 3809
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 3670
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 36098
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 495033868 (472.10 MB)
telemt_user_octets_to_client{user="hello"} 15301110060 (14.25 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 16724.4 (4h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40982
telemt_connections_bad_total 356
telemt_handshake_timeouts_total 1732
telemt_upstream_connect_attempt_total 6323
telemt_upstream_connect_success_total 6257
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 6323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3204
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 102909
telemt_me_reconnect_success_total 5052
telemt_me_reader_eof_total 5384
telemt_me_idle_close_by_peer_total 5384
telemt_me_route_drop_no_conn_total 16207
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36586
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 5311
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 5014
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 36670
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 2848183849 (2.65 GB)
telemt_user_octets_to_client{user="hello"} 19060333974 (17.75 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 16729.2 (4h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51909
telemt_connections_bad_total 120
telemt_handshake_timeouts_total 324
telemt_upstream_connect_attempt_total 4293
telemt_upstream_connect_success_total 4268
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 4293
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1936
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2312
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 3410
telemt_me_reconnect_success_total 3389
telemt_me_reader_eof_total 3535
telemt_me_idle_close_by_peer_total 3535
telemt_me_route_drop_no_conn_total 23835
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49242
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 432
telemt_desync_full_logged_total 113
telemt_desync_suppressed_total 319
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 179
telemt_desync_frames_bucket_total{bucket="gt_10"} 181
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 3424
telemt_me_writer_restored_same_endpoint_total 3387
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 49121
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 613580960 (585.16 MB)
telemt_user_octets_to_client{user="hello"} 16083506456 (14.98 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 16722.3 (4h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38474
telemt_connections_bad_total 3249
telemt_handshake_timeouts_total 1955
telemt_upstream_connect_attempt_total 3878
telemt_upstream_connect_success_total 3834
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 3878
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1678
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2138
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 9470
telemt_me_reconnect_success_total 2948
telemt_me_reader_eof_total 3243
telemt_me_idle_close_by_peer_total 3243
telemt_me_route_drop_no_conn_total 13158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31488
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 150
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 133
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 3175
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 2944
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 31481
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 548151156 (522.76 MB)
telemt_user_octets_to_client{user="hello"} 8275334564 (7.71 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 16721.9 (4h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136073
telemt_connections_bad_total 7095
telemt_handshake_timeouts_total 1635
telemt_upstream_connect_attempt_total 3460
telemt_upstream_connect_success_total 3393
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 3460
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1672
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1719
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 85
telemt_me_reconnect_attempts_total 7502
telemt_me_reconnect_success_total 2504
telemt_me_reader_eof_total 2732
telemt_me_idle_close_by_peer_total 2732
telemt_me_route_drop_no_conn_total 70821
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 121582
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2684
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 2500
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 120242
telemt_user_connections_current{user="hello"} 504
telemt_user_octets_from_client{user="hello"} 2902456092 (2.70 GB)
telemt_user_octets_to_client{user="hello"} 61870322120 (57.62 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 73
```