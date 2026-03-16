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

# Server Metrics 2026-03-16 18:32:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 17703.8 (4h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173677
telemt_connections_bad_total 850
telemt_handshake_timeouts_total 4294
telemt_upstream_connect_attempt_total 3701
telemt_upstream_connect_success_total 3688
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 3701
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1757
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1925
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3927
telemt_me_reconnect_success_total 2757
telemt_me_reader_eof_total 2872
telemt_me_idle_close_by_peer_total 2871
telemt_me_route_drop_no_conn_total 54143
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162795
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 838
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 644
telemt_desync_frames_bucket_total{bucket="1_2"} 310
telemt_desync_frames_bucket_total{bucket="3_10"} 301
telemt_desync_frames_bucket_total{bucket="gt_10"} 227
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2817
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2755
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 162708
telemt_user_connections_current{user="hello"} 605
telemt_user_octets_from_client{user="hello"} 3109499488 (2.90 GB)
telemt_user_octets_to_client{user="hello"} 92765319244 (86.39 GB)
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 12482.3 (3h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86029
telemt_connections_bad_total 644
telemt_handshake_timeouts_total 3298
telemt_upstream_connect_attempt_total 2647
telemt_upstream_connect_success_total 2634
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2647
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 956
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1447
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 231
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 5483
telemt_me_reconnect_success_total 1973
telemt_me_reader_eof_total 2128
telemt_me_idle_close_by_peer_total 2128
telemt_me_route_drop_no_conn_total 47967
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79042
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 143
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 111
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 65
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2115
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 1968
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 343
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 78983
telemt_user_connections_current{user="hello"} 385
telemt_user_octets_from_client{user="hello"} 913015568 (870.72 MB)
telemt_user_octets_to_client{user="hello"} 22487944104 (20.94 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 17816.6 (4h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71363
telemt_connections_bad_total 94
telemt_handshake_timeouts_total 916
telemt_upstream_connect_attempt_total 5141
telemt_upstream_connect_success_total 5089
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 5141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2658
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2399
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 42059
telemt_me_reconnect_success_total 3172
telemt_me_reader_eof_total 3547
telemt_me_idle_close_by_peer_total 3547
telemt_me_route_drop_no_conn_total 25283
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66109
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 165
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 73
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 3511
telemt_me_refill_failed_total 1214
telemt_me_writer_restored_same_endpoint_total 3128
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 339
telemt_user_connections_total{user="hello"} 67041
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 911470910 (869.25 MB)
telemt_user_octets_to_client{user="hello"} 19727392218 (18.37 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 17952.9 (4h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138303
telemt_connections_bad_total 249
telemt_handshake_timeouts_total 1861
telemt_upstream_connect_attempt_total 3820
telemt_upstream_connect_success_total 3794
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 3820
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1941
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 9187
telemt_me_reconnect_success_total 2829
telemt_me_reader_eof_total 3096
telemt_me_idle_close_by_peer_total 3095
telemt_me_route_drop_no_conn_total 50337
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 131302
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 677
telemt_desync_full_logged_total 193
telemt_desync_suppressed_total 484
telemt_desync_frames_bucket_total{bucket="1_2"} 118
telemt_desync_frames_bucket_total{bucket="3_10"} 278
telemt_desync_frames_bucket_total{bucket="gt_10"} 281
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 3065
telemt_me_refill_failed_total 197
telemt_me_writer_restored_same_endpoint_total 2825
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 236
telemt_user_connections_total{user="hello"} 131269
telemt_user_connections_current{user="hello"} 379
telemt_user_octets_from_client{user="hello"} 1835613096 (1.71 GB)
telemt_user_octets_to_client{user="hello"} 33064439792 (30.79 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 15413.3 (4h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77204
telemt_connections_bad_total 20747
telemt_handshake_timeouts_total 592
telemt_upstream_connect_attempt_total 4122
telemt_upstream_connect_success_total 4061
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 4122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2358
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_reconnect_attempts_total 4898
telemt_me_reconnect_success_total 3234
telemt_me_reader_eof_total 3342
telemt_me_idle_close_by_peer_total 3342
telemt_me_route_drop_no_conn_total 52756
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72057
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 73
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 47
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3391
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 3234
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 53097
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 2112303660 (1.97 GB)
telemt_user_octets_to_client{user="hello"} 34703791788 (32.32 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 17521.2 (4h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202078
telemt_connections_bad_total 3754
telemt_handshake_timeouts_total 3464
telemt_upstream_connect_attempt_total 3571
telemt_upstream_connect_success_total 3571
telemt_upstream_connect_attempts_per_request{bucket="1"} 3571
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1678
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1877
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7668
telemt_me_reconnect_success_total 2637
telemt_me_reader_eof_total 2867
telemt_me_idle_close_by_peer_total 2866
telemt_me_route_drop_no_conn_total 94515
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 186825
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 139
telemt_desync_full_logged_total 55
telemt_desync_suppressed_total 84
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2817
telemt_me_refill_failed_total 156
telemt_me_writer_restored_same_endpoint_total 2631
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 186428
telemt_user_connections_current{user="hello"} 673
telemt_user_octets_from_client{user="hello"} 3635095456 (3.39 GB)
telemt_user_octets_to_client{user="hello"} 67943812932 (63.28 GB)
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 91
```