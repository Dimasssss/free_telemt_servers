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

# Server Metrics 2026-03-14 21:24:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 29286.5 (8h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142337
telemt_connections_bad_total 16295
telemt_handshake_timeouts_total 1510
telemt_upstream_connect_attempt_total 6602
telemt_upstream_connect_success_total 6600
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 6602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3387
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 223
telemt_me_reconnect_attempts_total 5137
telemt_me_reconnect_success_total 5099
telemt_me_reader_eof_total 5414
telemt_me_idle_close_by_peer_total 5414
telemt_me_route_drop_no_conn_total 51664
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 118079
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 567
telemt_desync_full_logged_total 197
telemt_desync_suppressed_total 370
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 204
telemt_desync_frames_bucket_total{bucket="gt_10"} 236
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 5181
telemt_me_writer_restored_same_endpoint_total 5081
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 117999
telemt_user_connections_current{user="hello"} 244
telemt_user_octets_from_client{user="hello"} 2501507628 (2.33 GB)
telemt_user_octets_to_client{user="hello"} 71641154752 (66.72 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 29284.5 (8h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58990
telemt_connections_bad_total 734
telemt_handshake_timeouts_total 996
telemt_upstream_connect_attempt_total 7605
telemt_upstream_connect_success_total 7557
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 7605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3122
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4299
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 140
telemt_me_reconnect_attempts_total 8636
telemt_me_reconnect_success_total 6056
telemt_me_reader_eof_total 6445
telemt_me_idle_close_by_peer_total 6445
telemt_me_route_drop_no_conn_total 32060
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55039
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 6217
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 6051
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 54960
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 1379960156 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 24800792776 (23.10 GB)
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 29288.8 (8h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66343
telemt_connections_bad_total 393
telemt_handshake_timeouts_total 1912
telemt_upstream_connect_attempt_total 9587
telemt_upstream_connect_success_total 9487
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 9587
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4430
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5044
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 105533
telemt_me_reconnect_success_total 7668
telemt_me_reader_eof_total 8181
telemt_me_idle_close_by_peer_total 8181
telemt_me_route_drop_no_conn_total 24797
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60666
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 7950
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 7622
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 282
telemt_user_connections_total{user="hello"} 60729
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 3909401173 (3.64 GB)
telemt_user_octets_to_client{user="hello"} 45898755738 (42.75 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 29293.6 (8h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84219
telemt_connections_bad_total 207
telemt_handshake_timeouts_total 611
telemt_upstream_connect_attempt_total 7167
telemt_upstream_connect_success_total 7123
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 7167
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3344
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3749
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 202
telemt_me_reconnect_attempts_total 5486
telemt_me_reconnect_success_total 5458
telemt_me_reader_eof_total 5754
telemt_me_idle_close_by_peer_total 5754
telemt_me_route_drop_no_conn_total 36348
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79821
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 651
telemt_desync_full_logged_total 166
telemt_desync_suppressed_total 485
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 274
telemt_desync_frames_bucket_total{bucket="gt_10"} 261
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 5517
telemt_me_writer_restored_same_endpoint_total 5456
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 79865
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 1330862136 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 28492829586 (26.54 GB)
telemt_user_msgs_from_client{user="hello"} 473
telemt_user_msgs_to_client{user="hello"} 2783
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 29286.9 (8h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63129
telemt_connections_bad_total 5727
telemt_handshake_timeouts_total 3381
telemt_upstream_connect_attempt_total 7139
telemt_upstream_connect_success_total 7057
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 7139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3191
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3820
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 217
telemt_me_reconnect_attempts_total 12090
telemt_me_reconnect_success_total 5552
telemt_me_reader_eof_total 6013
telemt_me_idle_close_by_peer_total 6013
telemt_me_route_drop_no_conn_total 20399
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50894
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 270
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 229
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 136
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 5808
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 5548
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 256
telemt_user_connections_total{user="hello"} 50880
telemt_user_connections_current{user="hello"} 74
telemt_user_octets_from_client{user="hello"} 1406191960 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 31720863908 (29.54 GB)
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 29286.2 (8h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 212784
telemt_connections_bad_total 7327
telemt_handshake_timeouts_total 2678
telemt_upstream_connect_attempt_total 5854
telemt_upstream_connect_success_total 5745
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 5854
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2945
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 261
telemt_me_reconnect_attempts_total 9253
telemt_me_reconnect_success_total 4244
telemt_me_reader_eof_total 4595
telemt_me_idle_close_by_peer_total 4595
telemt_me_route_drop_no_conn_total 118690
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 196542
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 115
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 84
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4452
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 4240
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 193027
telemt_user_connections_current{user="hello"} 392
telemt_user_octets_from_client{user="hello"} 5126816844 (4.77 GB)
telemt_user_octets_to_client{user="hello"} 106009063836 (98.73 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 56
```