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

# Server Metrics 2026-03-15 14:07:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 57175.0 (15h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 256519
telemt_connections_bad_total 2350
telemt_handshake_timeouts_total 5921
telemt_upstream_connect_attempt_total 14458
telemt_upstream_connect_success_total 14383
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 14458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6390
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7975
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 14893
telemt_me_reconnect_success_total 11515
telemt_me_reader_eof_total 12274
telemt_me_idle_close_by_peer_total 12274
telemt_me_route_drop_no_conn_total 437035
telemt_me_route_drop_channel_closed_total 70
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 299492
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1684
telemt_desync_full_logged_total 665
telemt_desync_suppressed_total 1019
telemt_desync_frames_bucket_total{bucket="1_2"} 303
telemt_desync_frames_bucket_total{bucket="3_10"} 657
telemt_desync_frames_bucket_total{bucket="gt_10"} 724
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 11739
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 11484
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 224
telemt_user_connections_total{user="hello"} 238597
telemt_user_connections_current{user="hello"} 415
telemt_user_octets_from_client{user="hello"} 5263201996 (4.90 GB)
telemt_user_octets_to_client{user="hello"} 208174070144 (193.88 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 57182.0 (15h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94247
telemt_connections_bad_total 2748
telemt_handshake_timeouts_total 9089
telemt_upstream_connect_attempt_total 15747
telemt_upstream_connect_success_total 15747
telemt_upstream_connect_attempts_per_request{bucket="1"} 15747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8832
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 15197
telemt_me_reconnect_success_total 12849
telemt_me_reader_eof_total 13743
telemt_me_idle_close_by_peer_total 13743
telemt_me_route_drop_no_conn_total 39920
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79583
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 13071
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 12833
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 222
telemt_user_connections_total{user="hello"} 79574
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 1583511348 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 38430753656 (35.79 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 57174.0 (15h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98113
telemt_connections_bad_total 1619
telemt_handshake_timeouts_total 2762
telemt_upstream_connect_attempt_total 17000
telemt_upstream_connect_success_total 16992
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 17000
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9625
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 18708
telemt_me_reconnect_success_total 14088
telemt_me_reader_eof_total 15083
telemt_me_idle_close_by_peer_total 15083
telemt_me_route_drop_no_conn_total 38186
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 88291
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 3
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
telemt_me_writer_removed_unexpected_total 14365
telemt_me_refill_failed_total 142
telemt_me_writer_restored_same_endpoint_total 14080
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 277
telemt_user_connections_total{user="hello"} 88197
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 10101403096 (9.41 GB)
telemt_user_octets_to_client{user="hello"} 52506069412 (48.90 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 57173.6 (15h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134877
telemt_connections_bad_total 693
telemt_handshake_timeouts_total 886
telemt_upstream_connect_attempt_total 13599
telemt_upstream_connect_success_total 13596
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 13599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6512
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7040
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 10792
telemt_me_reconnect_success_total 10728
telemt_me_reader_eof_total 11429
telemt_me_idle_close_by_peer_total 11429
telemt_me_route_drop_no_conn_total 52531
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 123053
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 420
telemt_desync_full_logged_total 128
telemt_desync_suppressed_total 292
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 185
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 10852
telemt_me_writer_restored_same_endpoint_total 10717
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 122969
telemt_user_connections_current{user="hello"} 241
telemt_user_octets_from_client{user="hello"} 2333172440 (2.17 GB)
telemt_user_octets_to_client{user="hello"} 61970929176 (57.71 GB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 32245.0 (8h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77824
telemt_connections_bad_total 21070
telemt_handshake_timeouts_total 1413
telemt_upstream_connect_attempt_total 10250
telemt_upstream_connect_success_total 10184
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 10250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5526
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 102820
telemt_me_reconnect_success_total 8395
telemt_me_reader_eof_total 8777
telemt_me_idle_close_by_peer_total 8777
telemt_me_route_drop_no_conn_total 26152
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53599
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 150
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 119
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 61
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 8405
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 8291
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 53736
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 825036685 (786.82 MB)
telemt_user_octets_to_client{user="hello"} 21354474507 (19.89 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 57173.3 (15h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 341105
telemt_connections_bad_total 48341
telemt_handshake_timeouts_total 2730
telemt_upstream_connect_attempt_total 12252
telemt_upstream_connect_success_total 12179
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 12252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6097
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6079
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 9363
telemt_me_reconnect_success_total 9295
telemt_me_reader_eof_total 9870
telemt_me_idle_close_by_peer_total 9870
telemt_me_route_drop_no_conn_total 156808
telemt_me_route_drop_channel_closed_total 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 280123
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 296
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 218
telemt_desync_frames_bucket_total{bucket="1_2"} 163
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 9383
telemt_me_writer_restored_same_endpoint_total 9268
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 277988
telemt_user_connections_current{user="hello"} 583
telemt_user_octets_from_client{user="hello"} 6803782288 (6.34 GB)
telemt_user_octets_to_client{user="hello"} 136879991200 (127.48 GB)
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 66
```