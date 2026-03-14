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

# Server Metrics 2026-03-14 18:51:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 20092.9 (5h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 111624
telemt_connections_bad_total 15619
telemt_handshake_timeouts_total 989
telemt_upstream_connect_attempt_total 4732
telemt_upstream_connect_success_total 4730
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2251
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2404
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 180
telemt_me_reconnect_attempts_total 3701
telemt_me_reconnect_success_total 3669
telemt_me_reader_eof_total 3883
telemt_me_idle_close_by_peer_total 3883
telemt_me_route_drop_no_conn_total 39016
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 90265
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 353
telemt_desync_full_logged_total 129
telemt_desync_suppressed_total 224
telemt_desync_frames_bucket_total{bucket="1_2"} 88
telemt_desync_frames_bucket_total{bucket="3_10"} 132
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 3726
telemt_me_writer_restored_same_endpoint_total 3651
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 90193
telemt_user_connections_current{user="hello"} 291
telemt_user_octets_from_client{user="hello"} 1820733704 (1.70 GB)
telemt_user_octets_to_client{user="hello"} 44257933152 (41.22 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 20091.1 (5h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45154
telemt_connections_bad_total 504
telemt_handshake_timeouts_total 865
telemt_upstream_connect_attempt_total 5363
telemt_upstream_connect_success_total 5323
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 5362
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3067
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 6837
telemt_me_reconnect_success_total 4262
telemt_me_reader_eof_total 4529
telemt_me_idle_close_by_peer_total 4529
telemt_me_route_drop_no_conn_total 24286
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42162
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 4402
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 4257
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 42146
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 610235756 (581.97 MB)
telemt_user_octets_to_client{user="hello"} 18192111488 (16.94 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 20095.3 (5h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48522
telemt_connections_bad_total 374
telemt_handshake_timeouts_total 1807
telemt_upstream_connect_attempt_total 7154
telemt_upstream_connect_success_total 7076
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 7154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3399
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3673
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_timeout_total 175
telemt_me_reconnect_attempts_total 103556
telemt_me_reconnect_success_total 5696
telemt_me_reader_eof_total 6078
telemt_me_idle_close_by_peer_total 6078
telemt_me_route_drop_no_conn_total 19209
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43700
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 8
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
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 5961
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 5655
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 265
telemt_user_connections_total{user="hello"} 43765
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 3075695209 (2.86 GB)
telemt_user_octets_to_client{user="hello"} 24989784518 (23.27 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 20100.1 (5h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61812
telemt_connections_bad_total 175
telemt_handshake_timeouts_total 525
telemt_upstream_connect_attempt_total 4972
telemt_upstream_connect_success_total 4941
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 4972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2673
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 3909
telemt_me_reconnect_success_total 3888
telemt_me_reader_eof_total 4073
telemt_me_idle_close_by_peer_total 4073
telemt_me_route_drop_no_conn_total 27780
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 58410
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 507
telemt_desync_full_logged_total 128
telemt_desync_suppressed_total 379
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 206
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3929
telemt_me_writer_restored_same_endpoint_total 3886
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 58286
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 825030648 (786.81 MB)
telemt_user_octets_to_client{user="hello"} 18388727732 (17.13 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 20093.3 (5h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46370
telemt_connections_bad_total 3878
telemt_handshake_timeouts_total 2670
telemt_upstream_connect_attempt_total 4638
telemt_upstream_connect_success_total 4586
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 4638
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2041
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2520
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 10050
telemt_me_reconnect_success_total 3524
telemt_me_reader_eof_total 3862
telemt_me_idle_close_by_peer_total 3862
telemt_me_route_drop_no_conn_total 15959
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37560
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 202
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 176
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 113
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3760
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 3520
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 236
telemt_user_connections_total{user="hello"} 37551
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 594239700 (566.71 MB)
telemt_user_octets_to_client{user="hello"} 10754496356 (10.02 GB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 20092.9 (5h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 161708
telemt_connections_bad_total 7196
telemt_handshake_timeouts_total 2568
telemt_upstream_connect_attempt_total 4024
telemt_upstream_connect_success_total 3951
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 4024
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1951
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1998
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 96
telemt_me_reconnect_attempts_total 7888
telemt_me_reconnect_success_total 2889
telemt_me_reader_eof_total 3147
telemt_me_idle_close_by_peer_total 3147
telemt_me_route_drop_no_conn_total 85956
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 146218
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
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3074
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 2885
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 185
telemt_user_connections_total{user="hello"} 143663
telemt_user_connections_current{user="hello"} 472
telemt_user_octets_from_client{user="hello"} 3248727092 (3.03 GB)
telemt_user_octets_to_client{user="hello"} 74959693440 (69.81 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 71
```