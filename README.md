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

# Server Metrics 2026-03-15 10:12:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 43086.7 (11h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 177586
telemt_connections_bad_total 1274
telemt_handshake_timeouts_total 4137
telemt_upstream_connect_attempt_total 10801
telemt_upstream_connect_success_total 10743
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 10801
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4773
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5958
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 10973
telemt_me_reconnect_success_total 8605
telemt_me_reader_eof_total 9201
telemt_me_idle_close_by_peer_total 9201
telemt_me_route_drop_no_conn_total 408747
telemt_me_route_drop_channel_closed_total 60
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 226366
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1321
telemt_desync_full_logged_total 527
telemt_desync_suppressed_total 794
telemt_desync_frames_bucket_total{bucket="1_2"} 211
telemt_desync_frames_bucket_total{bucket="3_10"} 533
telemt_desync_frames_bucket_total{bucket="gt_10"} 577
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 8758
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 8574
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 153
telemt_user_connections_total{user="hello"} 165767
telemt_user_connections_current{user="hello"} 423
telemt_user_octets_from_client{user="hello"} 2515598624 (2.34 GB)
telemt_user_octets_to_client{user="hello"} 174025950252 (162.07 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 43093.4 (11h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56387
telemt_connections_bad_total 2293
telemt_handshake_timeouts_total 3038
telemt_upstream_connect_attempt_total 11613
telemt_upstream_connect_success_total 11612
telemt_upstream_connect_attempts_per_request{bucket="1"} 11612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6574
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 11771
telemt_me_reconnect_success_total 9449
telemt_me_reader_eof_total 10150
telemt_me_idle_close_by_peer_total 10150
telemt_me_route_drop_no_conn_total 26909
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49292
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 9624
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 9433
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 175
telemt_user_connections_total{user="hello"} 49291
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 993622356 (947.59 MB)
telemt_user_octets_to_client{user="hello"} 21147919952 (19.70 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 43085.5 (11h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63596
telemt_connections_bad_total 640
telemt_handshake_timeouts_total 2433
telemt_upstream_connect_attempt_total 11756
telemt_upstream_connect_success_total 11755
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11756
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5075
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6670
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 9649
telemt_me_reconnect_success_total 9603
telemt_me_reader_eof_total 10328
telemt_me_idle_close_by_peer_total 10328
telemt_me_route_drop_no_conn_total 24002
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57967
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 30
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 9692
telemt_me_writer_restored_same_endpoint_total 9599
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 57892
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 9274572476 (8.64 GB)
telemt_user_octets_to_client{user="hello"} 36147536364 (33.67 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 43085.4 (11h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82689
telemt_connections_bad_total 206
telemt_handshake_timeouts_total 580
telemt_upstream_connect_attempt_total 10180
telemt_upstream_connect_success_total 10179
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10180
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4840
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5309
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 8084
telemt_me_reconnect_success_total 8046
telemt_me_reader_eof_total 8594
telemt_me_idle_close_by_peer_total 8594
telemt_me_route_drop_no_conn_total 34760
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75118
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 157
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 110
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 64
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 8131
telemt_me_writer_restored_same_endpoint_total 8035
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 75048
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 1525632876 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 48418379044 (45.09 GB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 18156.7 (5h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30747
telemt_connections_bad_total 3403
telemt_handshake_timeouts_total 495
telemt_upstream_connect_attempt_total 6163
telemt_upstream_connect_success_total 6112
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 6163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2744
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_reconnect_attempts_total 99409
telemt_me_reconnect_success_total 5002
telemt_me_reader_eof_total 5181
telemt_me_idle_close_by_peer_total 5181
telemt_me_route_drop_no_conn_total 10286
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26082
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 40
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 33
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 4969
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 4898
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 26222
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 404543305 (385.80 MB)
telemt_user_octets_to_client{user="hello"} 12295988531 (11.45 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 43084.9 (11h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 225789
telemt_connections_bad_total 43184
telemt_handshake_timeouts_total 1446
telemt_upstream_connect_attempt_total 9205
telemt_upstream_connect_success_total 9150
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 9205
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4515
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_reconnect_attempts_total 7045
telemt_me_reconnect_success_total 7006
telemt_me_reader_eof_total 7464
telemt_me_idle_close_by_peer_total 7464
telemt_me_route_drop_no_conn_total 98563
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 175309
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 67
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 7055
telemt_me_writer_restored_same_endpoint_total 6979
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 173843
telemt_user_connections_current{user="hello"} 514
telemt_user_octets_from_client{user="hello"} 4342020436 (4.04 GB)
telemt_user_octets_to_client{user="hello"} 88679341976 (82.59 GB)
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 76
```