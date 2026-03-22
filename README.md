# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
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

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-22 09:24:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 44290.7 (12h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1108431
telemt_connections_bad_total 60362
telemt_connections_current 1686
telemt_connections_me_current 1686
telemt_handshake_timeouts_total 50640
telemt_upstream_connect_attempt_total 17408
telemt_upstream_connect_success_total 17407
telemt_upstream_connect_attempts_per_request{bucket="1"} 17407
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11286
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 41
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 494
telemt_me_reconnect_success_total 266
telemt_me_reader_eof_total 265
telemt_me_idle_close_by_peer_total 265
telemt_me_route_drop_no_conn_total 603162
telemt_me_route_drop_channel_closed_total 232
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 922748
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_endpoint_quarantine_total 315
telemt_me_single_endpoint_shadow_rotate_total 357
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 6598
telemt_desync_full_logged_total 1895
telemt_desync_suppressed_total 4703
telemt_desync_frames_bucket_total{bucket="1_2"} 1954
telemt_desync_frames_bucket_total{bucket="3_10"} 2482
telemt_desync_frames_bucket_total{bucket="gt_10"} 2162
telemt_pool_swap_total 49
telemt_pool_force_close_total 1394
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 167
telemt_me_draining_writers_reap_progress_total 15819
telemt_me_writer_removed_unexpected_total 261
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1101
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14931
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1364
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14425
telemt_me_writer_teardown_success_total{mode="normal"} 16032
telemt_me_writer_teardown_noop_total 15821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31853
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 63.360893
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31853
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 167
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 244
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 921056
telemt_user_connections_current{user="hello"} 1686
telemt_user_octets_from_client{user="hello"} 14461861176 (13.47 GB)
telemt_user_octets_to_client{user="hello"} 294420022112 (274.20 GB)
telemt_user_unique_ips_current{user="hello"} 557
telemt_user_unique_ips_recent_window{user="hello"} 484
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 57656.6 (16h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1663912
telemt_connections_bad_total 156481
telemt_connections_current 2343
telemt_connections_me_current 2343
telemt_handshake_timeouts_total 44937
telemt_upstream_connect_attempt_total 34342
telemt_upstream_connect_success_total 33899
telemt_upstream_connect_fail_total 389
telemt_upstream_connect_attempts_per_request{bucket="1"} 34288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14612
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 389
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 2576
telemt_me_reconnect_success_total 1098
telemt_me_reader_eof_total 992
telemt_me_idle_close_by_peer_total 992
telemt_me_route_drop_no_conn_total 881390
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1267308
telemt_me_endpoint_quarantine_total 505
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 26
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 26
telemt_me_single_endpoint_shadow_rotate_total 456
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 13
telemt_desync_total 5677
telemt_desync_full_logged_total 3269
telemt_desync_suppressed_total 2408
telemt_desync_frames_bucket_total{bucket="1_2"} 1260
telemt_desync_frames_bucket_total{bucket="3_10"} 2221
telemt_desync_frames_bucket_total{bucket="gt_10"} 2196
telemt_pool_swap_total 59
telemt_pool_force_close_total 1610
telemt_me_writer_close_signal_drop_total 132
telemt_me_draining_writers_reap_progress_total 23320
telemt_me_writer_removed_unexpected_total 960
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2299
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21972
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1486
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 124
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21710
telemt_me_writer_teardown_success_total{mode="normal"} 24271
telemt_me_writer_teardown_noop_total 23320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47591
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.175888
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47591
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 132
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 879
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 1273458
telemt_user_connections_current{user="hello"} 2343
telemt_user_octets_from_client{user="hello"} 18842411038 (17.55 GB)
telemt_user_octets_to_client{user="hello"} 408609456004 (380.55 GB)
telemt_user_msgs_from_client{user="hello"} 21111
telemt_user_msgs_to_client{user="hello"} 48002
telemt_user_unique_ips_current{user="hello"} 1442
telemt_user_unique_ips_recent_window{user="hello"} 753
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 132517.4 (36h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10271995
telemt_connections_bad_total 916135
telemt_connections_current 4423
telemt_connections_me_current 4423
telemt_handshake_timeouts_total 298825
telemt_upstream_connect_attempt_total 48745
telemt_upstream_connect_success_total 48665
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 48673
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22014
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26449
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 196
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1976
telemt_me_reconnect_success_total 1032
telemt_me_reader_eof_total 1029
telemt_me_idle_close_by_peer_total 1028
telemt_me_route_drop_no_conn_total 6254382
telemt_me_route_drop_channel_closed_total 87
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8084925
telemt_me_endpoint_quarantine_total 843
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 989
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 34821
telemt_desync_full_logged_total 11371
telemt_desync_suppressed_total 23450
telemt_desync_frames_bucket_total{bucket="1_2"} 7701
telemt_desync_frames_bucket_total{bucket="3_10"} 13541
telemt_desync_frames_bucket_total{bucket="gt_10"} 13579
telemt_pool_swap_total 143
telemt_pool_force_close_total 4779
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 732
telemt_me_draining_writers_reap_progress_total 44478
telemt_me_writer_removed_unexpected_total 989
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3762
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41162
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4460
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 319
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39699
telemt_me_writer_teardown_success_total{mode="normal"} 44924
telemt_me_writer_teardown_noop_total 44522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89446
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 198.024655
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89446
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 732
telemt_me_refill_failed_total 50
telemt_me_writer_restored_same_endpoint_total 913
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 8074779
telemt_user_connections_current{user="hello"} 4423
telemt_user_octets_from_client{user="hello"} 130561375880 (121.59 GB)
telemt_user_octets_to_client{user="hello"} 2613274476148 (2.38 TB)
telemt_user_unique_ips_current{user="hello"} 1513
telemt_user_unique_ips_recent_window{user="hello"} 1334
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 132517.8 (36h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8277171
telemt_connections_bad_total 744324
telemt_connections_current 4890
telemt_connections_me_current 4890
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 263109
telemt_upstream_connect_attempt_total 54740
telemt_upstream_connect_success_total 54249
telemt_upstream_connect_fail_total 247
telemt_upstream_connect_attempts_per_request{bucket="1"} 54496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26474
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26537
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 109
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 247
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2971
telemt_me_reconnect_success_total 1145
telemt_me_reader_eof_total 1059
telemt_me_idle_close_by_peer_total 1059
telemt_me_route_drop_no_conn_total 2870582
telemt_me_route_drop_channel_closed_total 333
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6129773
telemt_me_endpoint_quarantine_total 837
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 1020
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 78
telemt_me_writers_warm_current 12
telemt_desync_total 28180
telemt_desync_full_logged_total 9568
telemt_desync_suppressed_total 18612
telemt_desync_frames_bucket_total{bucket="1_2"} 6817
telemt_desync_frames_bucket_total{bucket="3_10"} 10909
telemt_desync_frames_bucket_total{bucket="gt_10"} 10454
telemt_pool_swap_total 144
telemt_pool_force_close_total 4337
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 470
telemt_me_draining_writers_reap_progress_total 42607
telemt_me_writer_removed_unexpected_total 1077
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3671
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39906
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4075
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 262
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38270
telemt_me_writer_teardown_success_total{mode="normal"} 43577
telemt_me_writer_teardown_noop_total 42613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86190
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 61.981390
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86190
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 470
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 970
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 6052091
telemt_user_connections_current{user="hello"} 4890
telemt_user_octets_from_client{user="hello"} 164455211375 (153.16 GB)
telemt_user_octets_to_client{user="hello"} 2875470381174 (2.62 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1945
telemt_user_unique_ips_recent_window{user="hello"} 638
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 132482.6 (36h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7931874
telemt_connections_bad_total 661729
telemt_connections_current 3691
telemt_connections_me_current 3691
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 261957
telemt_upstream_connect_attempt_total 59490
telemt_upstream_connect_success_total 58802
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 58949
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27703
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 958
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1344
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3406
telemt_me_reconnect_success_total 1448
telemt_me_reader_eof_total 1339
telemt_me_idle_close_by_peer_total 1339
telemt_me_route_drop_no_conn_total 3222992
telemt_me_route_drop_channel_closed_total 207
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5915542
telemt_me_endpoint_quarantine_total 921
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 973
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 27727
telemt_desync_full_logged_total 9443
telemt_desync_suppressed_total 18284
telemt_desync_frames_bucket_total{bucket="1_2"} 6703
telemt_desync_frames_bucket_total{bucket="3_10"} 10648
telemt_desync_frames_bucket_total{bucket="gt_10"} 10376
telemt_pool_swap_total 140
telemt_pool_force_close_total 4210
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 492
telemt_me_draining_writers_reap_progress_total 43740
telemt_me_writer_removed_unexpected_total 1364
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4093
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40983
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3834
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 376
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39530
telemt_me_writer_teardown_success_total{mode="normal"} 45076
telemt_me_writer_teardown_noop_total 43752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88828
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 50.918947
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88828
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 492
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 1275
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 5908209
telemt_user_connections_current{user="hello"} 3691
telemt_user_octets_from_client{user="hello"} 151185160583 (140.80 GB)
telemt_user_octets_to_client{user="hello"} 2617589289851 (2.38 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1428
telemt_user_unique_ips_recent_window{user="hello"} 575
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 2761.7 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1102769
telemt_connections_bad_total 90424
telemt_connections_current 6151
telemt_connections_me_current 6151
telemt_handshake_timeouts_total 13727
telemt_upstream_connect_attempt_total 7705
telemt_upstream_connect_success_total 7310
telemt_upstream_connect_fail_total 334
telemt_upstream_connect_attempts_per_request{bucket="1"} 7644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1137
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2662
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 334
telemt_me_keepalive_timeout_total 136
telemt_me_reconnect_attempts_total 303
telemt_me_reconnect_success_total 102
telemt_me_reader_eof_total 55
telemt_me_idle_close_by_peer_total 55
telemt_me_route_drop_no_conn_total 2316522
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 904253
telemt_me_endpoint_quarantine_total 15
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 29
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 5
telemt_desync_total 1481
telemt_desync_full_logged_total 388
telemt_desync_suppressed_total 1093
telemt_desync_frames_bucket_total{bucket="1_2"} 284
telemt_desync_frames_bucket_total{bucket="3_10"} 572
telemt_desync_frames_bucket_total{bucket="gt_10"} 625
telemt_pool_swap_total 1
telemt_pool_force_close_total 62
telemt_me_writer_close_signal_drop_total 40
telemt_me_draining_writers_reap_progress_total 708
telemt_me_writer_removed_unexpected_total 99
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 143
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 664
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 26
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 36
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 646
telemt_me_writer_teardown_success_total{mode="normal"} 807
telemt_me_writer_teardown_noop_total 708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1515
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.795757
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1515
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 40
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 59
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 910409
telemt_user_connections_current{user="hello"} 6151
telemt_user_octets_from_client{user="hello"} 5992295406 (5.58 GB)
telemt_user_octets_to_client{user="hello"} 28212865379 (26.28 GB)
telemt_user_msgs_from_client{user="hello"} 6014
telemt_user_msgs_to_client{user="hello"} 4995
telemt_user_unique_ips_current{user="hello"} 2288
telemt_user_unique_ips_recent_window{user="hello"} 1275
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 132488.5 (36h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7564168
telemt_connections_bad_total 677544
telemt_connections_current 3893
telemt_connections_me_current 3893
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 155043
telemt_upstream_connect_attempt_total 75645
telemt_upstream_connect_success_total 74821
telemt_upstream_connect_fail_total 706
telemt_upstream_connect_attempts_per_request{bucket="1"} 75527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28769
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 443
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 706
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70458
telemt_me_reconnect_success_total 2076
telemt_me_reader_eof_total 1821
telemt_me_idle_close_by_peer_total 1820
telemt_me_route_drop_no_conn_total 3026875
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5948122
telemt_me_endpoint_quarantine_total 894
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1000
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 30094
telemt_desync_full_logged_total 10425
telemt_desync_suppressed_total 19669
telemt_desync_frames_bucket_total{bucket="1_2"} 6037
telemt_desync_frames_bucket_total{bucket="3_10"} 11561
telemt_desync_frames_bucket_total{bucket="gt_10"} 12496
telemt_pool_swap_total 138
telemt_pool_force_close_total 3974
telemt_pool_stale_pick_total 66
telemt_me_writer_close_signal_drop_total 474
telemt_me_draining_writers_reap_progress_total 45998
telemt_me_writer_removed_unexpected_total 1850
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4690
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43185
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3490
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 484
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42024
telemt_me_writer_teardown_success_total{mode="normal"} 47875
telemt_me_writer_teardown_noop_total 45999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93874
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.535955
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93874
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 474
telemt_me_refill_failed_total 4230
telemt_me_writer_restored_same_endpoint_total 1722
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 5945987
telemt_user_connections_current{user="hello"} 3893
telemt_user_octets_from_client{user="hello"} 148953269175 (138.72 GB)
telemt_user_octets_to_client{user="hello"} 2438137871947 (2.22 TB)
telemt_user_msgs_from_client{user="hello"} 115484
telemt_user_msgs_to_client{user="hello"} 517108
telemt_user_unique_ips_current{user="hello"} 1466
telemt_user_unique_ips_recent_window{user="hello"} 617
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 69324.5 (19h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6200523
telemt_connections_bad_total 242120
telemt_connections_current 5141
telemt_connections_me_current 5141
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2498390
telemt_upstream_connect_attempt_total 36938
telemt_upstream_connect_success_total 36681
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 36931
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14982
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_reconnect_attempts_total 47466
telemt_me_reconnect_success_total 1243
telemt_me_reader_eof_total 908
telemt_me_idle_close_by_peer_total 908
telemt_me_route_drop_no_conn_total 1603871
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3087208
telemt_me_endpoint_quarantine_total 477
telemt_me_single_endpoint_outage_enter_total 14
telemt_me_single_endpoint_outage_exit_total 14
telemt_me_single_endpoint_outage_reconnect_attempt_total 53
telemt_me_single_endpoint_outage_reconnect_success_total 14
telemt_me_single_endpoint_quarantine_bypass_total 53
telemt_me_single_endpoint_shadow_rotate_total 527
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 16859
telemt_desync_full_logged_total 5696
telemt_desync_suppressed_total 11163
telemt_desync_frames_bucket_total{bucket="1_2"} 3326
telemt_desync_frames_bucket_total{bucket="3_10"} 6455
telemt_desync_frames_bucket_total{bucket="gt_10"} 7078
telemt_pool_swap_total 73
telemt_pool_force_close_total 2213
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 211
telemt_me_draining_writers_reap_progress_total 24956
telemt_me_writer_removed_unexpected_total 979
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2178
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23779
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1903
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 310
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22743
telemt_me_writer_teardown_success_total{mode="normal"} 25957
telemt_me_writer_teardown_noop_total 24962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50919
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.716114
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50919
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 211
telemt_me_refill_failed_total 2688
telemt_me_writer_restored_same_endpoint_total 1110
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3088003
telemt_user_connections_current{user="hello"} 5141
telemt_user_octets_from_client{user="hello"} 77428042680 (72.11 GB)
telemt_user_octets_to_client{user="hello"} 1328603593494 (1.21 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1944
telemt_user_unique_ips_recent_window{user="hello"} 689
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 50295.3 (13h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 469191
telemt_connections_bad_total 3669
telemt_connections_current 864
telemt_connections_me_current 864
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 8913
telemt_upstream_connect_attempt_total 26699
telemt_upstream_connect_success_total 26636
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 26694
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12478
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13894
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 264
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_reconnect_attempts_total 1123
telemt_me_reconnect_success_total 447
telemt_me_reader_eof_total 447
telemt_me_idle_close_by_peer_total 447
telemt_me_route_drop_no_conn_total 152675
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 423393
telemt_me_endpoint_quarantine_total 463
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 430
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 87
telemt_desync_total 1979
telemt_desync_full_logged_total 582
telemt_desync_suppressed_total 1397
telemt_desync_frames_bucket_total{bucket="1_2"} 573
telemt_desync_frames_bucket_total{bucket="3_10"} 769
telemt_desync_frames_bucket_total{bucket="gt_10"} 637
telemt_pool_swap_total 53
telemt_pool_force_close_total 1222
telemt_me_writer_close_signal_drop_total 47
telemt_me_draining_writers_reap_progress_total 21466
telemt_me_writer_removed_unexpected_total 430
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1554
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20359
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1194
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 28
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20244
telemt_me_writer_teardown_success_total{mode="normal"} 21913
telemt_me_writer_teardown_noop_total 21466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43379
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.981074
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43379
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 47
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 396
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 425522
telemt_user_connections_current{user="hello"} 864
telemt_user_octets_from_client{user="hello"} 8426823693 (7.85 GB)
telemt_user_octets_to_client{user="hello"} 211982169635 (197.42 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 325
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 132493.0 (36h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9307711
telemt_connections_bad_total 1080652
telemt_connections_current 3838
telemt_connections_me_current 3838
telemt_handshake_timeouts_total 254621
telemt_upstream_connect_attempt_total 51316
telemt_upstream_connect_success_total 51119
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 51270
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25789
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_reconnect_attempts_total 1921
telemt_me_reconnect_success_total 1049
telemt_me_reader_eof_total 1021
telemt_me_idle_close_by_peer_total 1021
telemt_me_route_drop_no_conn_total 2631998
telemt_me_route_drop_channel_closed_total 67
telemt_me_route_drop_queue_full_total 25
telemt_me_route_drop_queue_full_profile_total{profile="high"} 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6903054
telemt_me_endpoint_quarantine_total 940
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1005
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 27908
telemt_desync_full_logged_total 9148
telemt_desync_suppressed_total 18760
telemt_desync_frames_bucket_total{bucket="1_2"} 6888
telemt_desync_frames_bucket_total{bucket="3_10"} 10194
telemt_desync_frames_bucket_total{bucket="gt_10"} 10826
telemt_pool_swap_total 147
telemt_pool_force_close_total 3960
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 484
telemt_me_draining_writers_reap_progress_total 46282
telemt_me_writer_removed_unexpected_total 981
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3719
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43575
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3857
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 103
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42322
telemt_me_writer_teardown_success_total{mode="normal"} 47294
telemt_me_writer_teardown_noop_total 46284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93578
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.887318
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93578
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 484
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 920
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 6875735
telemt_user_connections_current{user="hello"} 3838
telemt_user_octets_from_client{user="hello"} 133377721028 (124.22 GB)
telemt_user_octets_to_client{user="hello"} 3225066444476 (2.93 TB)
telemt_user_unique_ips_current{user="hello"} 1232
telemt_user_unique_ips_recent_window{user="hello"} 1116
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 132489.6 (36h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8097641
telemt_connections_bad_total 902494
telemt_connections_current 5083
telemt_connections_me_current 5083
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 213386
telemt_upstream_connect_attempt_total 75734
telemt_upstream_connect_success_total 75197
telemt_upstream_connect_fail_total 468
telemt_upstream_connect_attempts_per_request{bucket="1"} 75665
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42053
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30270
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1965
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 468
telemt_me_reconnect_attempts_total 6496
telemt_me_reconnect_success_total 1512
telemt_me_reader_eof_total 1343
telemt_me_idle_close_by_peer_total 1343
telemt_me_seq_mismatch_total 63
telemt_me_route_drop_no_conn_total 2833282
telemt_me_route_drop_channel_closed_total 242
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6165196
telemt_me_endpoint_quarantine_total 1038
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 34
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 34
telemt_me_single_endpoint_shadow_rotate_total 1004
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 53
telemt_desync_total 26765
telemt_desync_full_logged_total 8894
telemt_desync_suppressed_total 17871
telemt_desync_frames_bucket_total{bucket="1_2"} 6593
telemt_desync_frames_bucket_total{bucket="3_10"} 9838
telemt_desync_frames_bucket_total{bucket="gt_10"} 10334
telemt_pool_swap_total 144
telemt_pool_force_close_total 3856
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 478
telemt_me_draining_writers_reap_progress_total 44866
telemt_me_writer_removed_unexpected_total 1360
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4353
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41935
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3576
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 280
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41010
telemt_me_writer_teardown_success_total{mode="normal"} 46288
telemt_me_writer_teardown_noop_total 44870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91158
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.298141
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91158
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 478
telemt_me_refill_failed_total 287
telemt_me_writer_restored_same_endpoint_total 1181
telemt_me_writer_restored_fallback_total 87
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 6173963
telemt_user_connections_current{user="hello"} 5083
telemt_user_octets_from_client{user="hello"} 112961159037 (105.20 GB)
telemt_user_octets_to_client{user="hello"} 2636247652695 (2.40 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1961
telemt_user_unique_ips_recent_window{user="hello"} 847
```