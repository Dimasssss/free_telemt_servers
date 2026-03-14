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

# Server Metrics 2026-03-14 11:37:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 187447.5 (52h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 737464
telemt_connections_bad_total 34476
telemt_handshake_timeouts_total 14354
telemt_upstream_connect_attempt_total 47722
telemt_upstream_connect_success_total 47486
telemt_upstream_connect_fail_total 236
telemt_upstream_connect_attempts_per_request{bucket="1"} 47722
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21736
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25596
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 236
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 6153
telemt_me_reconnect_attempts_total 43517
telemt_me_reconnect_success_total 37752
telemt_me_reader_eof_total 40366
telemt_me_idle_close_by_peer_total 40365
telemt_me_route_drop_no_conn_total 243417
telemt_me_route_drop_channel_closed_total 40
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 632593
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2646
telemt_desync_full_logged_total 881
telemt_desync_suppressed_total 1765
telemt_desync_frames_bucket_total{bucket="1_2"} 553
telemt_desync_frames_bucket_total{bucket="3_10"} 993
telemt_desync_frames_bucket_total{bucket="gt_10"} 1100
telemt_pool_swap_total 170
telemt_me_writer_removed_unexpected_total 38335
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 37732
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 583
telemt_user_connections_total{user="hello"} 632491
telemt_user_connections_current{user="hello"} 372
telemt_user_octets_from_client{user="hello"} 17653176782 (16.44 GB)
telemt_user_octets_to_client{user="hello"} 304451032344 (283.54 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 187341.1 (52h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 366420
telemt_connections_bad_total 2837
telemt_handshake_timeouts_total 3307
telemt_upstream_connect_attempt_total 155666
telemt_upstream_connect_success_total 154281
telemt_upstream_connect_fail_total 1384
telemt_upstream_connect_attempts_per_request{bucket="1"} 155665
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 112120
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39683
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2477
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1384
telemt_me_keepalive_timeout_total 5549
telemt_me_reconnect_attempts_total 193652
telemt_me_reconnect_success_total 41616
telemt_me_reader_eof_total 47446
telemt_me_idle_close_by_peer_total 47446
telemt_me_route_drop_no_conn_total 126692
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 242858
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 46764
telemt_me_refill_failed_total 4743
telemt_me_writer_restored_same_endpoint_total 41598
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5148
telemt_user_connections_total{user="hello"} 345956
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 3525736679 (3.28 GB)
telemt_user_octets_to_client{user="hello"} 111760448027 (104.09 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 187304.7 (52h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 423512
telemt_connections_bad_total 3307
telemt_handshake_timeouts_total 36391
telemt_upstream_connect_attempt_total 50007
telemt_upstream_connect_success_total 49998
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 50007
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26935
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4111
telemt_me_reconnect_attempts_total 41861
telemt_me_reconnect_success_total 40542
telemt_me_reader_eof_total 43555
telemt_me_idle_close_by_peer_total 43555
telemt_me_route_drop_no_conn_total 154603
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 368648
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 138
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 175
telemt_me_writer_removed_unexpected_total 41030
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 40521
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 488
telemt_user_connections_total{user="hello"} 368411
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 15157773410 (14.12 GB)
telemt_user_octets_to_client{user="hello"} 161950709495 (150.83 GB)
telemt_user_msgs_from_client{user="hello"} 166
telemt_user_msgs_to_client{user="hello"} 712
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 187280.7 (52h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 536362
telemt_connections_bad_total 16770
telemt_handshake_timeouts_total 5289
telemt_upstream_connect_attempt_total 80241
telemt_upstream_connect_success_total 69543
telemt_upstream_connect_fail_total 10697
telemt_upstream_connect_attempts_per_request{bucket="1"} 80240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40457
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28702
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 375
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10697
telemt_me_keepalive_timeout_total 5732
telemt_me_reconnect_attempts_total 155817
telemt_me_reconnect_success_total 41177
telemt_me_reader_eof_total 46078
telemt_me_idle_close_by_peer_total 46070
telemt_me_route_drop_no_conn_total 194686
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 460162
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2086
telemt_desync_full_logged_total 615
telemt_desync_suppressed_total 1471
telemt_desync_frames_bucket_total{bucket="1_2"} 487
telemt_desync_frames_bucket_total{bucket="3_10"} 792
telemt_desync_frames_bucket_total{bucket="gt_10"} 807
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 45227
telemt_me_refill_failed_total 3574
telemt_me_writer_restored_same_endpoint_total 41167
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 4050
telemt_user_connections_total{user="hello"} 479028
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 10126358723 (9.43 GB)
telemt_user_octets_to_client{user="hello"} 195575549772 (182.14 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 137451.9 (38h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 232417
telemt_connections_bad_total 36862
telemt_handshake_timeouts_total 2141
telemt_upstream_connect_attempt_total 48189
telemt_upstream_connect_success_total 47707
telemt_upstream_connect_fail_total 482
telemt_upstream_connect_attempts_per_request{bucket="1"} 48189
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23786
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23760
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 482
telemt_me_keepalive_timeout_total 2951
telemt_me_reconnect_attempts_total 51867
telemt_me_reconnect_success_total 35980
telemt_me_reader_eof_total 38486
telemt_me_idle_close_by_peer_total 38486
telemt_me_route_drop_no_conn_total 70445
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 182315
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 789
telemt_desync_full_logged_total 193
telemt_desync_suppressed_total 596
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 287
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 36812
telemt_me_refill_failed_total 492
telemt_me_writer_restored_same_endpoint_total 35962
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 832
telemt_user_connections_total{user="hello"} 187071
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 2740063153 (2.55 GB)
telemt_user_octets_to_client{user="hello"} 86151156207 (80.23 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 187236.6 (52h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1090897
telemt_connections_bad_total 37486
telemt_handshake_timeouts_total 27122
telemt_upstream_connect_attempt_total 39061
telemt_upstream_connect_success_total 38857
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 39061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18401
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20415
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_keepalive_timeout_total 4967
telemt_me_reconnect_attempts_total 34299
telemt_me_reconnect_success_total 29606
telemt_me_reader_eof_total 31743
telemt_me_idle_close_by_peer_total 31740
telemt_me_route_drop_no_conn_total 511993
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1011675
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 809
telemt_desync_full_logged_total 268
telemt_desync_suppressed_total 541
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 280
telemt_pool_swap_total 174
telemt_me_writer_removed_unexpected_total 30127
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 29599
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 521
telemt_user_connections_total{user="hello"} 984260
telemt_user_connections_current{user="hello"} 472
telemt_user_octets_from_client{user="hello"} 21115285520 (19.67 GB)
telemt_user_octets_to_client{user="hello"} 493523724256 (459.63 GB)
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 64
```