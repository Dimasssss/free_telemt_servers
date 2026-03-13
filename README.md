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

# Server Metrics 2026-03-13 05:35:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 79338.7 (22h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 301395
telemt_connections_bad_total 3068
telemt_handshake_timeouts_total 6175
telemt_upstream_connect_attempt_total 19989
telemt_upstream_connect_success_total 19895
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 19989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8904
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10943
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1561
telemt_me_reconnect_attempts_total 19388
telemt_me_reconnect_success_total 15891
telemt_me_reader_eof_total 16989
telemt_me_idle_close_by_peer_total 16988
telemt_me_route_drop_no_conn_total 94108
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 253933
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 864
telemt_desync_full_logged_total 322
telemt_desync_suppressed_total 542
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 315
telemt_desync_frames_bucket_total{bucket="gt_10"} 378
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 16171
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 15875
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 280
telemt_user_connections_total{user="hello"} 253870
telemt_user_connections_current{user="hello"} 279
telemt_user_octets_from_client{user="hello"} 4328616452 (4.03 GB)
telemt_user_octets_to_client{user="hello"} 123562762696 (115.08 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 79231.3 (22h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137561
telemt_connections_bad_total 759
telemt_handshake_timeouts_total 1040
telemt_upstream_connect_attempt_total 41946
telemt_upstream_connect_success_total 41416
telemt_upstream_connect_fail_total 530
telemt_upstream_connect_attempts_per_request{bucket="1"} 41946
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16233
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 508
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 530
telemt_me_keepalive_timeout_total 590
telemt_me_reconnect_attempts_total 67537
telemt_me_reconnect_success_total 20973
telemt_me_reader_eof_total 23077
telemt_me_idle_close_by_peer_total 23077
telemt_me_route_drop_no_conn_total 51183
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 114229
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 22592
telemt_me_refill_failed_total 1453
telemt_me_writer_restored_same_endpoint_total 20958
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1619
telemt_user_connections_total{user="hello"} 130727
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 1356805320 (1.26 GB)
telemt_user_octets_to_client{user="hello"} 39617182295 (36.90 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 79194.9 (21h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166537
telemt_connections_bad_total 1860
telemt_handshake_timeouts_total 2692
telemt_upstream_connect_attempt_total 21817
telemt_upstream_connect_success_total 21814
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 21816
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11757
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 464
telemt_me_reconnect_attempts_total 19001
telemt_me_reconnect_success_total 17833
telemt_me_reader_eof_total 19104
telemt_me_idle_close_by_peer_total 19104
telemt_me_route_drop_no_conn_total 64658
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 155771
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 18028
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 17813
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 155698
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 2915757688 (2.72 GB)
telemt_user_octets_to_client{user="hello"} 71176436628 (66.29 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 79170.4 (21h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 240446
telemt_connections_bad_total 13565
telemt_handshake_timeouts_total 1799
telemt_upstream_connect_attempt_total 33982
telemt_upstream_connect_success_total 24083
telemt_upstream_connect_fail_total 9899
telemt_upstream_connect_attempts_per_request{bucket="1"} 33982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11778
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 168
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9899
telemt_me_keepalive_timeout_total 3317
telemt_me_reconnect_attempts_total 68814
telemt_me_reconnect_success_total 17283
telemt_me_reader_eof_total 19416
telemt_me_idle_close_by_peer_total 19409
telemt_me_route_drop_no_conn_total 87871
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 201661
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 568
telemt_desync_full_logged_total 162
telemt_desync_suppressed_total 406
telemt_desync_frames_bucket_total{bucket="1_2"} 141
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 213
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 19117
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 17273
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1834
telemt_user_connections_total{user="hello"} 204404
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 3295467270 (3.07 GB)
telemt_user_octets_to_client{user="hello"} 81325734425 (75.74 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 29342.1 (8h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31218
telemt_connections_bad_total 5513
telemt_handshake_timeouts_total 133
telemt_upstream_connect_attempt_total 9811
telemt_upstream_connect_success_total 9718
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 9811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5451
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 9201
telemt_me_reconnect_success_total 8242
telemt_me_reader_eof_total 8807
telemt_me_idle_close_by_peer_total 8807
telemt_me_route_drop_no_conn_total 8814
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 24734
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 8348
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 8224
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 24734
telemt_user_connections_current{user="hello"} 62
telemt_user_octets_from_client{user="hello"} 198827944 (189.62 MB)
telemt_user_octets_to_client{user="hello"} 9412272776 (8.77 GB)
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 79127.0 (21h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 406011
telemt_connections_bad_total 7758
telemt_handshake_timeouts_total 3052
telemt_upstream_connect_attempt_total 16834
telemt_upstream_connect_success_total 16740
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 16834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8920
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 1450
telemt_me_reconnect_attempts_total 16450
telemt_me_reconnect_success_total 12819
telemt_me_reader_eof_total 13764
telemt_me_idle_close_by_peer_total 13761
telemt_me_route_drop_no_conn_total 180347
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 394274
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 342
telemt_desync_full_logged_total 131
telemt_desync_suppressed_total 211
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 124
telemt_desync_frames_bucket_total{bucket="gt_10"} 137
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 13096
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 12812
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 277
telemt_user_connections_total{user="hello"} 382524
telemt_user_connections_current{user="hello"} 327
telemt_user_octets_from_client{user="hello"} 6320715064 (5.89 GB)
telemt_user_octets_to_client{user="hello"} 224105603708 (208.71 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 52
```