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

# Server Metrics 2026-03-14 20:18:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 25304.2 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131477
telemt_connections_bad_total 16052
telemt_handshake_timeouts_total 1289
telemt_upstream_connect_attempt_total 5726
telemt_upstream_connect_success_total 5724
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2725
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2919
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 191
telemt_me_reconnect_attempts_total 4437
telemt_me_reconnect_success_total 4402
telemt_me_reader_eof_total 4668
telemt_me_idle_close_by_peer_total 4668
telemt_me_route_drop_no_conn_total 47126
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 108325
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 462
telemt_desync_full_logged_total 166
telemt_desync_suppressed_total 296
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 169
telemt_desync_frames_bucket_total{bucket="gt_10"} 179
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 4475
telemt_me_writer_restored_same_endpoint_total 4384
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 108246
telemt_user_connections_current{user="hello"} 361
telemt_user_octets_from_client{user="hello"} 2343606028 (2.18 GB)
telemt_user_octets_to_client{user="hello"} 60286843868 (56.15 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 25302.2 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53356
telemt_connections_bad_total 683
telemt_handshake_timeouts_total 953
telemt_upstream_connect_attempt_total 6539
telemt_upstream_connect_success_total 6497
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 6539
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2647
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3729
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 123
telemt_me_reconnect_attempts_total 7749
telemt_me_reconnect_success_total 5173
telemt_me_reader_eof_total 5502
telemt_me_idle_close_by_peer_total 5502
telemt_me_route_drop_no_conn_total 27946
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49670
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 5325
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 5168
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 152
telemt_user_connections_total{user="hello"} 49658
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 1302366568 (1.21 GB)
telemt_user_octets_to_client{user="hello"} 21216020640 (19.76 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 25306.6 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59778
telemt_connections_bad_total 389
telemt_handshake_timeouts_total 1868
telemt_upstream_connect_attempt_total 8460
telemt_upstream_connect_success_total 8371
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 8460
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3943
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4420
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 104597
telemt_me_reconnect_success_total 6734
telemt_me_reader_eof_total 7189
telemt_me_idle_close_by_peer_total 7189
telemt_me_route_drop_no_conn_total 22926
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54390
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 9
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
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 7008
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 6692
telemt_me_writer_restored_fallback_total 42
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 274
telemt_user_connections_total{user="hello"} 54455
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 3782640273 (3.52 GB)
telemt_user_octets_to_client{user="hello"} 40295182494 (37.53 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 25311.3 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76652
telemt_connections_bad_total 204
telemt_handshake_timeouts_total 576
telemt_upstream_connect_attempt_total 6242
telemt_upstream_connect_success_total 6204
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 6242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3260
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 183
telemt_me_reconnect_attempts_total 4740
telemt_me_reconnect_success_total 4715
telemt_me_reader_eof_total 4954
telemt_me_idle_close_by_peer_total 4954
telemt_me_route_drop_no_conn_total 33243
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72519
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 590
telemt_desync_full_logged_total 150
telemt_desync_suppressed_total 440
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 247
telemt_desync_frames_bucket_total{bucket="gt_10"} 244
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4769
telemt_me_writer_restored_same_endpoint_total 4713
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 72567
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 1112459224 (1.04 GB)
telemt_user_octets_to_client{user="hello"} 23424414998 (21.82 GB)
telemt_user_msgs_from_client{user="hello"} 473
telemt_user_msgs_to_client{user="hello"} 2783
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 25304.6 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55998
telemt_connections_bad_total 4888
telemt_handshake_timeouts_total 3275
telemt_upstream_connect_attempt_total 5915
telemt_upstream_connect_success_total 5845
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 5915
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3192
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 11059
telemt_me_reconnect_success_total 4525
telemt_me_reader_eof_total 4929
telemt_me_idle_close_by_peer_total 4929
telemt_me_route_drop_no_conn_total 18653
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45173
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 252
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 214
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4772
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 4521
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 45160
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 1362055844 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 26532088432 (24.71 GB)
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 25304.1 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194201
telemt_connections_bad_total 7288
telemt_handshake_timeouts_total 2627
telemt_upstream_connect_attempt_total 4950
telemt_upstream_connect_success_total 4858
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 4950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2382
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2471
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 249
telemt_me_reconnect_attempts_total 8547
telemt_me_reconnect_success_total 3541
telemt_me_reader_eof_total 3840
telemt_me_idle_close_by_peer_total 3840
telemt_me_route_drop_no_conn_total 109193
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 178568
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 55
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 35
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 3738
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 3537
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 197
telemt_user_connections_total{user="hello"} 175057
telemt_user_connections_current{user="hello"} 407
telemt_user_octets_from_client{user="hello"} 3827073052 (3.56 GB)
telemt_user_octets_to_client{user="hello"} 86674184216 (80.72 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 42
```