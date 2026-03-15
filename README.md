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

# Server Metrics 2026-03-15 09:06:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 39106.6 (10h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148465
telemt_connections_bad_total 1142
telemt_handshake_timeouts_total 3743
telemt_upstream_connect_attempt_total 9644
telemt_upstream_connect_success_total 9589
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 9644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4251
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5328
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 8848
telemt_me_reconnect_success_total 7635
telemt_me_reader_eof_total 8166
telemt_me_idle_close_by_peer_total 8166
telemt_me_route_drop_no_conn_total 321647
telemt_me_route_drop_channel_closed_total 44
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 188710
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1085
telemt_desync_full_logged_total 448
telemt_desync_suppressed_total 637
telemt_desync_frames_bucket_total{bucket="1_2"} 185
telemt_desync_frames_bucket_total{bucket="3_10"} 440
telemt_desync_frames_bucket_total{bucket="gt_10"} 460
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7741
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 7604
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 138160
telemt_user_connections_current{user="hello"} 360
telemt_user_octets_from_client{user="hello"} 1858110240 (1.73 GB)
telemt_user_octets_to_client{user="hello"} 142158708548 (132.40 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 39114.2 (10h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45748
telemt_connections_bad_total 298
telemt_handshake_timeouts_total 2548
telemt_upstream_connect_attempt_total 10668
telemt_upstream_connect_success_total 10668
telemt_upstream_connect_attempts_per_request{bucket="1"} 10668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6063
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 11003
telemt_me_reconnect_success_total 8689
telemt_me_reader_eof_total 9351
telemt_me_idle_close_by_peer_total 9351
telemt_me_route_drop_no_conn_total 23272
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41316
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 8849
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 8673
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 41317
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 903037400 (861.20 MB)
telemt_user_octets_to_client{user="hello"} 15534010152 (14.47 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 39106.8 (10h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55092
telemt_connections_bad_total 496
telemt_handshake_timeouts_total 1930
telemt_upstream_connect_attempt_total 10369
telemt_upstream_connect_success_total 10368
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5827
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 8443
telemt_me_reconnect_success_total 8400
telemt_me_reader_eof_total 9083
telemt_me_idle_close_by_peer_total 9083
telemt_me_route_drop_no_conn_total 19697
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50359
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 26
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 8480
telemt_me_writer_restored_same_endpoint_total 8396
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 50289
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 9069457260 (8.45 GB)
telemt_user_octets_to_client{user="hello"} 32932646296 (30.67 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 39106.5 (10h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68588
telemt_connections_bad_total 181
telemt_handshake_timeouts_total 422
telemt_upstream_connect_attempt_total 9355
telemt_upstream_connect_success_total 9354
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9355
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4408
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4918
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 7432
telemt_me_reconnect_success_total 7401
telemt_me_reader_eof_total 7909
telemt_me_idle_close_by_peer_total 7909
telemt_me_route_drop_no_conn_total 29357
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62325
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 133
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 93
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7476
telemt_me_writer_restored_same_endpoint_total 7390
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 62258
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 1240560076 (1.16 GB)
telemt_user_octets_to_client{user="hello"} 38405725968 (35.77 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 14177.9 (3h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22948
telemt_connections_bad_total 2695
telemt_handshake_timeouts_total 350
telemt_upstream_connect_attempt_total 4946
telemt_upstream_connect_success_total 4902
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 4946
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2175
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2714
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_reconnect_attempts_total 98420
telemt_me_reconnect_success_total 4016
telemt_me_reader_eof_total 4133
telemt_me_idle_close_by_peer_total 4133
telemt_me_route_drop_no_conn_total 7176
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19280
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 3975
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 3912
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 19420
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 174042553 (165.98 MB)
telemt_user_octets_to_client{user="hello"} 10654542343 (9.92 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 39105.7 (10h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176093
telemt_connections_bad_total 22242
telemt_handshake_timeouts_total 1003
telemt_upstream_connect_attempt_total 8414
telemt_upstream_connect_success_total 8364
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 8414
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4248
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4115
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_reconnect_attempts_total 6437
telemt_me_reconnect_success_total 6404
telemt_me_reader_eof_total 6832
telemt_me_idle_close_by_peer_total 6832
telemt_me_route_drop_no_conn_total 83912
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 148122
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 45
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 6443
telemt_me_writer_restored_same_endpoint_total 6377
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 146664
telemt_user_connections_current{user="hello"} 471
telemt_user_octets_from_client{user="hello"} 4027237624 (3.75 GB)
telemt_user_octets_to_client{user="hello"} 76303771684 (71.06 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 68
```