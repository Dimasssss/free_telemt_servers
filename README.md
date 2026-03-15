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

# Server Metrics 2026-03-15 14:38:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 59012.0 (16h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 266326
telemt_connections_bad_total 2473
telemt_handshake_timeouts_total 6910
telemt_upstream_connect_attempt_total 14884
telemt_upstream_connect_success_total 14807
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 14884
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8238
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 15230
telemt_me_reconnect_success_total 11850
telemt_me_reader_eof_total 12637
telemt_me_idle_close_by_peer_total 12637
telemt_me_route_drop_no_conn_total 440493
telemt_me_route_drop_channel_closed_total 72
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 307501
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1705
telemt_desync_full_logged_total 679
telemt_desync_suppressed_total 1026
telemt_desync_frames_bucket_total{bucket="1_2"} 305
telemt_desync_frames_bucket_total{bucket="3_10"} 666
telemt_desync_frames_bucket_total{bucket="gt_10"} 734
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 12077
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 11819
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 246608
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 5409324848 (5.04 GB)
telemt_user_octets_to_client{user="hello"} 213522886260 (198.86 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 59018.8 (16h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98791
telemt_connections_bad_total 2783
telemt_handshake_timeouts_total 9601
telemt_upstream_connect_attempt_total 16298
telemt_upstream_connect_success_total 16298
telemt_upstream_connect_attempts_per_request{bucket="1"} 16298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9142
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 15658
telemt_me_reconnect_success_total 13305
telemt_me_reader_eof_total 14223
telemt_me_idle_close_by_peer_total 14223
telemt_me_route_drop_no_conn_total 41893
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 83383
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 13534
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 13289
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 83374
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 1626813712 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 39921984700 (37.18 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 59010.9 (16h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107832
telemt_connections_bad_total 1649
telemt_handshake_timeouts_total 2790
telemt_upstream_connect_attempt_total 17467
telemt_upstream_connect_success_total 17459
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 17467
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9890
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 21800
telemt_me_reconnect_success_total 14460
telemt_me_reader_eof_total 15538
telemt_me_idle_close_by_peer_total 15538
telemt_me_route_drop_no_conn_total 40412
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92828
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 55
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 14822
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 14452
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 362
telemt_user_connections_total{user="hello"} 92729
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 10166246280 (9.47 GB)
telemt_user_octets_to_client{user="hello"} 54369982384 (50.64 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 59010.6 (16h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142027
telemt_connections_bad_total 790
telemt_handshake_timeouts_total 920
telemt_upstream_connect_attempt_total 14162
telemt_upstream_connect_success_total 14158
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 14162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7294
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 11268
telemt_me_reconnect_success_total 11198
telemt_me_reader_eof_total 11906
telemt_me_idle_close_by_peer_total 11906
telemt_me_route_drop_no_conn_total 55242
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 129826
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 457
telemt_desync_full_logged_total 144
telemt_desync_suppressed_total 313
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 207
telemt_desync_frames_bucket_total{bucket="gt_10"} 155
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 11329
telemt_me_writer_restored_same_endpoint_total 11187
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 129743
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 2450504484 (2.28 GB)
telemt_user_octets_to_client{user="hello"} 64034020204 (59.64 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 34082.0 (9h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82136
telemt_connections_bad_total 21405
telemt_handshake_timeouts_total 1425
telemt_upstream_connect_attempt_total 10726
telemt_upstream_connect_success_total 10659
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 10726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4849
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5768
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 103207
telemt_me_reconnect_success_total 8778
telemt_me_reader_eof_total 9180
telemt_me_idle_close_by_peer_total 9180
telemt_me_route_drop_no_conn_total 28035
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57429
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 155
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 65
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 8795
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 8674
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 57566
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 847633505 (808.37 MB)
telemt_user_octets_to_client{user="hello"} 23192856687 (21.60 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 59010.6 (16h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 356685
telemt_connections_bad_total 48477
telemt_handshake_timeouts_total 2970
telemt_upstream_connect_attempt_total 12690
telemt_upstream_connect_success_total 12614
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 12690
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6273
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6337
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 10925
telemt_me_reconnect_success_total 9638
telemt_me_reader_eof_total 10270
telemt_me_idle_close_by_peer_total 10270
telemt_me_route_drop_no_conn_total 166046
telemt_me_route_drop_channel_closed_total 40
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 294599
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 301
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 222
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 9768
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 9611
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 292446
telemt_user_connections_current{user="hello"} 623
telemt_user_octets_from_client{user="hello"} 7311367108 (6.81 GB)
telemt_user_octets_to_client{user="hello"} 146714604044 (136.64 GB)
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 84
```