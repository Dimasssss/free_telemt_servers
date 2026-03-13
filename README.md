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

# Server Metrics 2026-03-13 02:31:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 68285.7 (18h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 271344
telemt_connections_bad_total 2811
telemt_handshake_timeouts_total 5646
telemt_upstream_connect_attempt_total 17293
telemt_upstream_connect_success_total 17218
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 17293
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9560
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1521
telemt_me_reconnect_attempts_total 17271
telemt_me_reconnect_success_total 13789
telemt_me_reader_eof_total 14725
telemt_me_idle_close_by_peer_total 14724
telemt_me_route_drop_no_conn_total 84384
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 225842
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 742
telemt_desync_full_logged_total 279
telemt_desync_suppressed_total 463
telemt_desync_frames_bucket_total{bucket="1_2"} 136
telemt_desync_frames_bucket_total{bucket="3_10"} 274
telemt_desync_frames_bucket_total{bucket="gt_10"} 332
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 14046
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 13773
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 225608
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 4006228748 (3.73 GB)
telemt_user_octets_to_client{user="hello"} 111043050264 (103.42 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 68178.6 (18h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125750
telemt_connections_bad_total 742
telemt_handshake_timeouts_total 982
telemt_upstream_connect_attempt_total 37504
telemt_upstream_connect_success_total 37046
telemt_upstream_connect_fail_total 458
telemt_upstream_connect_attempts_per_request{bucket="1"} 37504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22932
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13612
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 502
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 458
telemt_me_keepalive_timeout_total 483
telemt_me_reconnect_attempts_total 61351
telemt_me_reconnect_success_total 17133
telemt_me_reader_eof_total 19000
telemt_me_idle_close_by_peer_total 19000
telemt_me_route_drop_no_conn_total 45278
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 102905
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 18645
telemt_me_refill_failed_total 1380
telemt_me_writer_restored_same_endpoint_total 17118
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1512
telemt_user_connections_total{user="hello"} 119405
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 1261813952 (1.18 GB)
telemt_user_octets_to_client{user="hello"} 35586395983 (33.14 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 68142.1 (18h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151538
telemt_connections_bad_total 1822
telemt_handshake_timeouts_total 2423
telemt_upstream_connect_attempt_total 18948
telemt_upstream_connect_success_total 18946
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 18948
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10163
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 379
telemt_me_reconnect_attempts_total 16652
telemt_me_reconnect_success_total 15492
telemt_me_reader_eof_total 16561
telemt_me_idle_close_by_peer_total 16561
telemt_me_route_drop_no_conn_total 57812
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 141668
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 52
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 15662
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 15472
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 141606
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 2717249236 (2.53 GB)
telemt_user_octets_to_client{user="hello"} 67108087752 (62.50 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 68117.9 (18h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216584
telemt_connections_bad_total 13412
telemt_handshake_timeouts_total 1429
telemt_upstream_connect_attempt_total 31259
telemt_upstream_connect_success_total 21459
telemt_upstream_connect_fail_total 9800
telemt_upstream_connect_attempts_per_request{bucket="1"} 31259
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10448
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9800
telemt_me_keepalive_timeout_total 3270
telemt_me_reconnect_attempts_total 54676
telemt_me_reconnect_success_total 15184
telemt_me_reader_eof_total 16918
telemt_me_idle_close_by_peer_total 16911
telemt_me_route_drop_no_conn_total 78519
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 179882
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 499
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 356
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 16630
telemt_me_refill_failed_total 1230
telemt_me_writer_restored_same_endpoint_total 15174
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1446
telemt_user_connections_total{user="hello"} 182633
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 3059282658 (2.85 GB)
telemt_user_octets_to_client{user="hello"} 75630966045 (70.44 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 18289.6 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16867
telemt_connections_bad_total 3428
telemt_handshake_timeouts_total 27
telemt_upstream_connect_attempt_total 5639
telemt_upstream_connect_success_total 5585
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 5639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3106
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 4658
telemt_me_reconnect_success_total 4641
telemt_me_reader_eof_total 4980
telemt_me_idle_close_by_peer_total 4980
telemt_me_route_drop_no_conn_total 4952
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12924
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4680
telemt_me_writer_restored_same_endpoint_total 4625
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 12924
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 83627116 (79.75 MB)
telemt_user_octets_to_client{user="hello"} 6226161560 (5.80 GB)
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 68074.4 (18h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 364694
telemt_connections_bad_total 6623
telemt_handshake_timeouts_total 2846
telemt_upstream_connect_attempt_total 14519
telemt_upstream_connect_success_total 14437
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 14519
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6749
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7666
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 1352
telemt_me_reconnect_attempts_total 14667
telemt_me_reconnect_success_total 11046
telemt_me_reader_eof_total 11859
telemt_me_idle_close_by_peer_total 11857
telemt_me_route_drop_no_conn_total 163377
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 356551
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 301
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 114
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 11294
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 11039
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 248
telemt_user_connections_total{user="hello"} 344809
telemt_user_connections_current{user="hello"} 272
telemt_user_octets_from_client{user="hello"} 5828620560 (5.43 GB)
telemt_user_octets_to_client{user="hello"} 203499857880 (189.52 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 40
```