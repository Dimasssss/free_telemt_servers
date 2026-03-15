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

# Server Metrics 2026-03-15 23:38:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 91470.4 (25h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 405213
telemt_connections_bad_total 5346
telemt_handshake_timeouts_total 14086
telemt_upstream_connect_attempt_total 21860
telemt_upstream_connect_success_total 21755
telemt_upstream_connect_fail_total 105
telemt_upstream_connect_attempts_per_request{bucket="1"} 21860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12080
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 105
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 20625
telemt_me_reconnect_success_total 17217
telemt_me_reader_eof_total 18381
telemt_me_idle_close_by_peer_total 18381
telemt_me_route_drop_no_conn_total 488884
telemt_me_route_drop_channel_closed_total 78
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 431728
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2125
telemt_desync_full_logged_total 840
telemt_desync_suppressed_total 1285
telemt_desync_frames_bucket_total{bucket="1_2"} 411
telemt_desync_frames_bucket_total{bucket="3_10"} 816
telemt_desync_frames_bucket_total{bucket="gt_10"} 898
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 17512
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 17183
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 295
telemt_user_connections_total{user="hello"} 370790
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 8066213588 (7.51 GB)
telemt_user_octets_to_client{user="hello"} 277504373300 (258.45 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 91477.1 (25h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169505
telemt_connections_bad_total 2906
telemt_handshake_timeouts_total 14229
telemt_upstream_connect_attempt_total 24908
telemt_upstream_connect_success_total 24833
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 24908
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10810
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13415
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 608
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1305
telemt_me_reconnect_attempts_total 26772
telemt_me_reconnect_success_total 19876
telemt_me_reader_eof_total 21265
telemt_me_idle_close_by_peer_total 21264
telemt_me_route_drop_no_conn_total 68900
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 145469
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 20386
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 19860
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 510
telemt_user_connections_total{user="hello"} 145737
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 3371630493 (3.14 GB)
telemt_user_octets_to_client{user="hello"} 76474876948 (71.22 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 91469.5 (25h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167729
telemt_connections_bad_total 1769
telemt_handshake_timeouts_total 3523
telemt_upstream_connect_attempt_total 26072
telemt_upstream_connect_success_total 26064
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 26072
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14736
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 28839
telemt_me_reconnect_success_total 21464
telemt_me_reader_eof_total 23079
telemt_me_idle_close_by_peer_total 23078
telemt_me_route_drop_no_conn_total 66140
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 149780
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 21903
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 21456
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 439
telemt_user_connections_total{user="hello"} 149662
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 13088749068 (12.19 GB)
telemt_user_octets_to_client{user="hello"} 97414862988 (90.72 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 91469.4 (25h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 246801
telemt_connections_bad_total 1203
telemt_handshake_timeouts_total 1626
telemt_upstream_connect_attempt_total 21333
telemt_upstream_connect_success_total 21313
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 21333
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10998
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 16874
telemt_me_reconnect_success_total 16774
telemt_me_reader_eof_total 17879
telemt_me_idle_close_by_peer_total 17879
telemt_me_route_drop_no_conn_total 89685
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 228049
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 867
telemt_desync_full_logged_total 299
telemt_desync_suppressed_total 568
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 368
telemt_desync_frames_bucket_total{bucket="gt_10"} 324
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 16972
telemt_me_writer_restored_same_endpoint_total 16763
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 198
telemt_user_connections_total{user="hello"} 227961
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 4096919788 (3.82 GB)
telemt_user_octets_to_client{user="hello"} 106538085592 (99.22 GB)
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 66540.9 (18h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155811
telemt_connections_bad_total 28634
telemt_handshake_timeouts_total 2818
telemt_upstream_connect_attempt_total 19135
telemt_upstream_connect_success_total 19024
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 19134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10363
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 110014
telemt_me_reconnect_success_total 15554
telemt_me_reader_eof_total 16444
telemt_me_idle_close_by_peer_total 16444
telemt_me_route_drop_no_conn_total 49505
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119985
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 337
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 127
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 15669
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 15450
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 120110
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 1775067777 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 42721267203 (39.79 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 91468.6 (25h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 615028
telemt_connections_bad_total 58624
telemt_handshake_timeouts_total 4748
telemt_upstream_connect_attempt_total 19320
telemt_upstream_connect_success_total 19212
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 19320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9989
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 15961
telemt_me_reconnect_success_total 14645
telemt_me_reader_eof_total 15597
telemt_me_idle_close_by_peer_total 15597
telemt_me_route_drop_no_conn_total 564903
telemt_me_route_drop_channel_closed_total 95
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 654452
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 326
telemt_desync_full_logged_total 92
telemt_desync_suppressed_total 234
telemt_desync_frames_bucket_total{bucket="1_2"} 170
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 14852
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 14618
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 207
telemt_user_connections_total{user="hello"} 514921
telemt_user_connections_current{user="hello"} 315
telemt_user_octets_from_client{user="hello"} 12525578376 (11.67 GB)
telemt_user_octets_to_client{user="hello"} 318824330132 (296.93 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 38
```