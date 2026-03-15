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

# Server Metrics 2026-03-15 14:02:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 56868.5 (15h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 254657
telemt_connections_bad_total 2322
telemt_handshake_timeouts_total 5806
telemt_upstream_connect_attempt_total 14359
telemt_upstream_connect_success_total 14284
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 14359
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7908
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 14794
telemt_me_reconnect_success_total 11416
telemt_me_reader_eof_total 12175
telemt_me_idle_close_by_peer_total 12175
telemt_me_route_drop_no_conn_total 436365
telemt_me_route_drop_channel_closed_total 70
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 297896
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1683
telemt_desync_full_logged_total 664
telemt_desync_suppressed_total 1019
telemt_desync_frames_bucket_total{bucket="1_2"} 303
telemt_desync_frames_bucket_total{bucket="3_10"} 657
telemt_desync_frames_bucket_total{bucket="gt_10"} 723
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 11639
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 11385
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 223
telemt_user_connections_total{user="hello"} 237002
telemt_user_connections_current{user="hello"} 453
telemt_user_octets_from_client{user="hello"} 5232855056 (4.87 GB)
telemt_user_octets_to_client{user="hello"} 207637304268 (193.38 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 56874.6 (15h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93624
telemt_connections_bad_total 2747
telemt_handshake_timeouts_total 9032
telemt_upstream_connect_attempt_total 15637
telemt_upstream_connect_success_total 15637
telemt_upstream_connect_attempts_per_request{bucket="1"} 15637
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6737
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8765
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 15087
telemt_me_reconnect_success_total 12740
telemt_me_reader_eof_total 13632
telemt_me_idle_close_by_peer_total 13632
telemt_me_route_drop_no_conn_total 39769
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79026
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
telemt_me_writer_removed_unexpected_total 12960
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 12724
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 220
telemt_user_connections_total{user="hello"} 79018
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 1579830172 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 38154226672 (35.53 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 56867.7 (15h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96063
telemt_connections_bad_total 1619
telemt_handshake_timeouts_total 2761
telemt_upstream_connect_attempt_total 16910
telemt_upstream_connect_success_total 16902
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 16910
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9568
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 18362
telemt_me_reconnect_success_total 14000
telemt_me_reader_eof_total 14986
telemt_me_idle_close_by_peer_total 14986
telemt_me_route_drop_no_conn_total 37752
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87636
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
telemt_me_writer_removed_unexpected_total 14268
telemt_me_refill_failed_total 134
telemt_me_writer_restored_same_endpoint_total 13992
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 268
telemt_user_connections_total{user="hello"} 87542
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 10087357424 (9.39 GB)
telemt_user_octets_to_client{user="hello"} 52368300964 (48.77 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 56866.9 (15h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133557
telemt_connections_bad_total 668
telemt_handshake_timeouts_total 880
telemt_upstream_connect_attempt_total 13549
telemt_upstream_connect_success_total 13546
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 13549
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7013
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 10742
telemt_me_reconnect_success_total 10679
telemt_me_reader_eof_total 11377
telemt_me_idle_close_by_peer_total 11377
telemt_me_route_drop_no_conn_total 51728
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 121804
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 419
telemt_desync_full_logged_total 127
telemt_desync_suppressed_total 292
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 184
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 10801
telemt_me_writer_restored_same_endpoint_total 10668
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 121720
telemt_user_connections_current{user="hello"} 247
telemt_user_octets_from_client{user="hello"} 2317911964 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 61724794832 (57.49 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 31938.5 (8h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77059
telemt_connections_bad_total 21015
telemt_handshake_timeouts_total 1409
telemt_upstream_connect_attempt_total 10213
telemt_upstream_connect_success_total 10147
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 10213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5505
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 102783
telemt_me_reconnect_success_total 8358
telemt_me_reader_eof_total 8740
telemt_me_idle_close_by_peer_total 8740
telemt_me_route_drop_no_conn_total 25843
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52922
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 148
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 118
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 8368
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 8254
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 53059
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 817267537 (779.41 MB)
telemt_user_octets_to_client{user="hello"} 21121746415 (19.67 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 56866.8 (15h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 338770
telemt_connections_bad_total 48247
telemt_handshake_timeouts_total 2705
telemt_upstream_connect_attempt_total 12142
telemt_upstream_connect_success_total 12069
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 12142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6041
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6025
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 9253
telemt_me_reconnect_success_total 9188
telemt_me_reader_eof_total 9762
telemt_me_idle_close_by_peer_total 9762
telemt_me_route_drop_no_conn_total 155700
telemt_me_route_drop_channel_closed_total 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 277980
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
telemt_me_writer_removed_unexpected_total 9274
telemt_me_writer_restored_same_endpoint_total 9161
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 275843
telemt_user_connections_current{user="hello"} 636
telemt_user_octets_from_client{user="hello"} 6768936724 (6.30 GB)
telemt_user_octets_to_client{user="hello"} 135425447516 (126.12 GB)
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 84
```