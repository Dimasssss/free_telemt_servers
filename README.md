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

# Server Metrics 2026-03-14 18:56:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 20399.6 (5h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112646
telemt_connections_bad_total 15639
telemt_handshake_timeouts_total 1000
telemt_upstream_connect_attempt_total 4784
telemt_upstream_connect_success_total 4782
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4784
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2440
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 181
telemt_me_reconnect_attempts_total 3753
telemt_me_reconnect_success_total 3720
telemt_me_reader_eof_total 3935
telemt_me_idle_close_by_peer_total 3935
telemt_me_route_drop_no_conn_total 39520
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91181
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 357
telemt_desync_full_logged_total 131
telemt_desync_suppressed_total 226
telemt_desync_frames_bucket_total{bucket="1_2"} 91
telemt_desync_frames_bucket_total{bucket="3_10"} 133
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 3778
telemt_me_writer_restored_same_endpoint_total 3702
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 91109
telemt_user_connections_current{user="hello"} 283
telemt_user_octets_from_client{user="hello"} 1829008172 (1.70 GB)
telemt_user_octets_to_client{user="hello"} 44418101836 (41.37 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 20398.0 (5h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45639
telemt_connections_bad_total 505
telemt_handshake_timeouts_total 866
telemt_upstream_connect_attempt_total 5413
telemt_upstream_connect_success_total 5374
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 5413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3099
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 6887
telemt_me_reconnect_success_total 4313
telemt_me_reader_eof_total 4579
telemt_me_idle_close_by_peer_total 4579
telemt_me_route_drop_no_conn_total 24427
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42634
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
telemt_me_writer_removed_unexpected_total 4452
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 4308
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 42618
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 624661924 (595.72 MB)
telemt_user_octets_to_client{user="hello"} 18305203676 (17.05 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 20402.2 (5h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49159
telemt_connections_bad_total 374
telemt_handshake_timeouts_total 1809
telemt_upstream_connect_attempt_total 7224
telemt_upstream_connect_success_total 7146
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 7224
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3718
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_timeout_total 175
telemt_me_reconnect_attempts_total 103626
telemt_me_reconnect_success_total 5765
telemt_me_reader_eof_total 6147
telemt_me_idle_close_by_peer_total 6147
telemt_me_route_drop_no_conn_total 19433
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44298
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
telemt_me_writer_removed_unexpected_total 6030
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 5724
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 265
telemt_user_connections_total{user="hello"} 44363
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 3082604201 (2.87 GB)
telemt_user_octets_to_client{user="hello"} 25275986742 (23.54 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 20407.0 (5h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62740
telemt_connections_bad_total 176
telemt_handshake_timeouts_total 528
telemt_upstream_connect_attempt_total 5022
telemt_upstream_connect_success_total 4991
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 5022
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2702
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 3959
telemt_me_reconnect_success_total 3937
telemt_me_reader_eof_total 4122
telemt_me_idle_close_by_peer_total 4122
telemt_me_route_drop_no_conn_total 28028
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59254
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 514
telemt_desync_full_logged_total 129
telemt_desync_suppressed_total 385
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 206
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3978
telemt_me_writer_restored_same_endpoint_total 3935
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 59130
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 829706280 (791.27 MB)
telemt_user_octets_to_client{user="hello"} 18654151324 (17.37 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 20399.9 (5h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47032
telemt_connections_bad_total 3953
telemt_handshake_timeouts_total 2851
telemt_upstream_connect_attempt_total 4681
telemt_upstream_connect_success_total 4629
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 4681
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2544
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 10093
telemt_me_reconnect_success_total 3567
telemt_me_reader_eof_total 3907
telemt_me_idle_close_by_peer_total 3907
telemt_me_route_drop_no_conn_total 16068
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37928
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 216
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 187
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 119
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3805
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 3563
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 37919
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 596429828 (568.80 MB)
telemt_user_octets_to_client{user="hello"} 11042994240 (10.28 GB)
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 20399.6 (5h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164090
telemt_connections_bad_total 7206
telemt_handshake_timeouts_total 2574
telemt_upstream_connect_attempt_total 4057
telemt_upstream_connect_success_total 3984
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 4057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1968
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2014
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 96
telemt_me_reconnect_attempts_total 7921
telemt_me_reconnect_success_total 2922
telemt_me_reader_eof_total 3180
telemt_me_idle_close_by_peer_total 3180
telemt_me_route_drop_no_conn_total 87603
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 148974
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
telemt_me_writer_removed_unexpected_total 3107
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 2918
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 185
telemt_user_connections_total{user="hello"} 145986
telemt_user_connections_current{user="hello"} 509
telemt_user_octets_from_client{user="hello"} 3274555124 (3.05 GB)
telemt_user_octets_to_client{user="hello"} 75890595916 (70.68 GB)
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 60
```