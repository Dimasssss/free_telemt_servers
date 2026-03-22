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

# Server Metrics 2026-03-22 10:00:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 46429.5 (12h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1198093
telemt_connections_bad_total 64383
telemt_connections_current 1687
telemt_connections_me_current 1687
telemt_handshake_timeouts_total 55164
telemt_upstream_connect_attempt_total 18061
telemt_upstream_connect_success_total 18060
telemt_upstream_connect_attempts_per_request{bucket="1"} 18060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6279
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11727
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 43
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 547
telemt_me_reconnect_success_total 279
telemt_me_reader_eof_total 278
telemt_me_idle_close_by_peer_total 278
telemt_me_route_drop_no_conn_total 634434
telemt_me_route_drop_channel_closed_total 267
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 997634
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_endpoint_quarantine_total 326
telemt_me_single_endpoint_shadow_rotate_total 374
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
telemt_desync_total 6901
telemt_desync_full_logged_total 2006
telemt_desync_suppressed_total 4895
telemt_desync_frames_bucket_total{bucket="1_2"} 2020
telemt_desync_frames_bucket_total{bucket="3_10"} 2612
telemt_desync_frames_bucket_total{bucket="gt_10"} 2269
telemt_pool_swap_total 51
telemt_pool_force_close_total 1485
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 179
telemt_me_draining_writers_reap_progress_total 16441
telemt_me_writer_removed_unexpected_total 275
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1136
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15502
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1454
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 31
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14956
telemt_me_writer_teardown_success_total{mode="normal"} 16638
telemt_me_writer_teardown_noop_total 16443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33081
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 72.784843
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33081
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 179
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 255
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 995846
telemt_user_connections_current{user="hello"} 1687
telemt_user_octets_from_client{user="hello"} 15687733280 (14.61 GB)
telemt_user_octets_to_client{user="hello"} 318644030640 (296.76 GB)
telemt_user_unique_ips_current{user="hello"} 647
telemt_user_unique_ips_recent_window{user="hello"} 273
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 59795.7 (16h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1817599
telemt_connections_bad_total 164766
telemt_connections_current 1424
telemt_connections_me_current 1424
telemt_handshake_timeouts_total 47687
telemt_upstream_connect_attempt_total 35673
telemt_upstream_connect_success_total 35203
telemt_upstream_connect_fail_total 415
telemt_upstream_connect_attempts_per_request{bucket="1"} 35618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19799
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15325
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 415
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3122
telemt_me_reconnect_success_total 1376
telemt_me_reader_eof_total 1273
telemt_me_idle_close_by_peer_total 1273
telemt_me_route_drop_no_conn_total 1033863
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1397281
telemt_me_endpoint_quarantine_total 511
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 473
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
telemt_me_writers_active_current 46
telemt_desync_total 6201
telemt_desync_full_logged_total 3542
telemt_desync_suppressed_total 2659
telemt_desync_frames_bucket_total{bucket="1_2"} 1392
telemt_desync_frames_bucket_total{bucket="3_10"} 2431
telemt_desync_frames_bucket_total{bucket="gt_10"} 2378
telemt_pool_swap_total 60
telemt_pool_force_close_total 1692
telemt_me_writer_close_signal_drop_total 137
telemt_me_draining_writers_reap_progress_total 24293
telemt_me_writer_removed_unexpected_total 1240
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2646
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22880
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1513
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 179
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22601
telemt_me_writer_teardown_success_total{mode="normal"} 25526
telemt_me_writer_teardown_noop_total 24293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49819
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.488569
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49819
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 137
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 1150
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 1403355
telemt_user_connections_current{user="hello"} 1424
telemt_user_octets_from_client{user="hello"} 20380920314 (18.98 GB)
telemt_user_octets_to_client{user="hello"} 440185239648 (409.95 GB)
telemt_user_msgs_from_client{user="hello"} 21111
telemt_user_msgs_to_client{user="hello"} 48002
telemt_user_unique_ips_current{user="hello"} 860
telemt_user_unique_ips_recent_window{user="hello"} 753
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 134655.4 (37h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10653993
telemt_connections_bad_total 948925
telemt_connections_current 5634
telemt_connections_me_current 5634
telemt_handshake_timeouts_total 304644
telemt_upstream_connect_attempt_total 49381
telemt_upstream_connect_success_total 49301
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 49309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26795
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 198
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2083
telemt_me_reconnect_success_total 1068
telemt_me_reader_eof_total 1059
telemt_me_idle_close_by_peer_total 1058
telemt_me_route_drop_no_conn_total 6675962
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8406877
telemt_me_endpoint_quarantine_total 857
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 1004
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_me_writers_active_current 42
telemt_desync_total 36118
telemt_desync_full_logged_total 11766
telemt_desync_suppressed_total 24352
telemt_desync_frames_bucket_total{bucket="1_2"} 8079
telemt_desync_frames_bucket_total{bucket="3_10"} 14020
telemt_desync_frames_bucket_total{bucket="gt_10"} 14019
telemt_pool_swap_total 145
telemt_pool_force_close_total 4851
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 749
telemt_me_draining_writers_reap_progress_total 45030
telemt_me_writer_removed_unexpected_total 1017
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3828
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41669
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4524
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 327
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40179
telemt_me_writer_teardown_success_total{mode="normal"} 45497
telemt_me_writer_teardown_noop_total 45074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90571
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 202.735138
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90571
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 749
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 937
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 8396459
telemt_user_connections_current{user="hello"} 5634
telemt_user_octets_from_client{user="hello"} 134000687796 (124.80 GB)
telemt_user_octets_to_client{user="hello"} 2667435796892 (2.43 TB)
telemt_user_unique_ips_current{user="hello"} 2084
telemt_user_unique_ips_recent_window{user="hello"} 920
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 134656.9 (37h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8531772
telemt_connections_bad_total 773894
telemt_connections_current 4433
telemt_connections_me_current 4433
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 267255
telemt_upstream_connect_attempt_total 55552
telemt_upstream_connect_success_total 55056
telemt_upstream_connect_fail_total 252
telemt_upstream_connect_attempts_per_request{bucket="1"} 55308
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26840
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26974
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 109
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 252
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 3022
telemt_me_reconnect_success_total 1182
telemt_me_reader_eof_total 1087
telemt_me_idle_close_by_peer_total 1087
telemt_me_route_drop_no_conn_total 2949527
telemt_me_route_drop_channel_closed_total 350
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6310265
telemt_me_endpoint_quarantine_total 856
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 1036
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
telemt_me_writers_active_current 43
telemt_desync_total 28916
telemt_desync_full_logged_total 9814
telemt_desync_suppressed_total 19102
telemt_desync_frames_bucket_total{bucket="1_2"} 6984
telemt_desync_frames_bucket_total{bucket="3_10"} 11202
telemt_desync_frames_bucket_total{bucket="gt_10"} 10730
telemt_pool_swap_total 146
telemt_pool_force_close_total 4430
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 490
telemt_me_draining_writers_reap_progress_total 43381
telemt_me_writer_removed_unexpected_total 1103
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3755
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40624
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4128
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 302
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38951
telemt_me_writer_teardown_success_total{mode="normal"} 44379
telemt_me_writer_teardown_noop_total 43387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87766
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 63.341393
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87766
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 490
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 1002
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 6232232
telemt_user_connections_current{user="hello"} 4433
telemt_user_octets_from_client{user="hello"} 168248088283 (156.69 GB)
telemt_user_octets_to_client{user="hello"} 2958241611062 (2.69 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1773
telemt_user_unique_ips_recent_window{user="hello"} 663
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 134620.9 (37h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8178629
telemt_connections_bad_total 690563
telemt_connections_current 4276
telemt_connections_me_current 4276
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 266489
telemt_upstream_connect_attempt_total 60122
telemt_upstream_connect_success_total 59424
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 59571
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28003
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 981
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1363
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3420
telemt_me_reconnect_success_total 1461
telemt_me_reader_eof_total 1349
telemt_me_idle_close_by_peer_total 1349
telemt_me_route_drop_no_conn_total 3390104
telemt_me_route_drop_channel_closed_total 221
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6106764
telemt_me_endpoint_quarantine_total 925
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 987
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
telemt_me_writers_active_current 46
telemt_desync_total 28479
telemt_desync_full_logged_total 9683
telemt_desync_suppressed_total 18796
telemt_desync_frames_bucket_total{bucket="1_2"} 6876
telemt_desync_frames_bucket_total{bucket="3_10"} 10942
telemt_desync_frames_bucket_total{bucket="gt_10"} 10661
telemt_pool_swap_total 142
telemt_pool_force_close_total 4324
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 510
telemt_me_draining_writers_reap_progress_total 44336
telemt_me_writer_removed_unexpected_total 1376
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4146
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41512
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3941
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 383
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40012
telemt_me_writer_teardown_success_total{mode="normal"} 45658
telemt_me_writer_teardown_noop_total 44353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90011
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.204138
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90011
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 510
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 1287
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 6099198
telemt_user_connections_current{user="hello"} 4276
telemt_user_octets_from_client{user="hello"} 153772976939 (143.21 GB)
telemt_user_octets_to_client{user="hello"} 2672120029019 (2.43 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1708
telemt_user_unique_ips_recent_window{user="hello"} 639
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 4900.6 (1h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2062750
telemt_connections_bad_total 164409
telemt_connections_current 6620
telemt_connections_me_current 6620
telemt_handshake_timeouts_total 26192
telemt_upstream_connect_attempt_total 8347
telemt_upstream_connect_success_total 7908
telemt_upstream_connect_fail_total 339
telemt_upstream_connect_attempts_per_request{bucket="1"} 8247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1446
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2679
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 339
telemt_me_keepalive_timeout_total 188
telemt_me_reconnect_attempts_total 357
telemt_me_reconnect_success_total 121
telemt_me_reader_eof_total 69
telemt_me_idle_close_by_peer_total 69
telemt_me_route_drop_no_conn_total 4611115
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1703599
telemt_me_endpoint_quarantine_total 25
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 42
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_desync_total 2598
telemt_desync_full_logged_total 656
telemt_desync_suppressed_total 1942
telemt_desync_frames_bucket_total{bucket="1_2"} 492
telemt_desync_frames_bucket_total{bucket="3_10"} 981
telemt_desync_frames_bucket_total{bucket="gt_10"} 1125
telemt_pool_swap_total 4
telemt_pool_force_close_total 156
telemt_me_writer_close_signal_drop_total 62
telemt_me_draining_writers_reap_progress_total 1253
telemt_me_writer_removed_unexpected_total 113
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 210
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1156
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 108
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 48
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1097
telemt_me_writer_teardown_success_total{mode="normal"} 1366
telemt_me_writer_teardown_noop_total 1253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2619
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.297103
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2619
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 62
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 73
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 1709444
telemt_user_connections_current{user="hello"} 6620
telemt_user_octets_from_client{user="hello"} 9452896862 (8.80 GB)
telemt_user_octets_to_client{user="hello"} 49927634859 (46.50 GB)
telemt_user_msgs_from_client{user="hello"} 6014
telemt_user_msgs_to_client{user="hello"} 4995
telemt_user_unique_ips_current{user="hello"} 2387
telemt_user_unique_ips_recent_window{user="hello"} 1390
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 134627.4 (37h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7784034
telemt_connections_bad_total 688790
telemt_connections_current 4845
telemt_connections_me_current 4845
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 160585
telemt_upstream_connect_attempt_total 76330
telemt_upstream_connect_success_total 75497
telemt_upstream_connect_fail_total 713
telemt_upstream_connect_attempts_per_request{bucket="1"} 76210
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29140
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 444
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 713
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70509
telemt_me_reconnect_success_total 2127
telemt_me_reader_eof_total 1872
telemt_me_idle_close_by_peer_total 1871
telemt_me_route_drop_no_conn_total 3190806
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6134274
telemt_me_endpoint_quarantine_total 896
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1013
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
telemt_me_writers_active_current 87
telemt_desync_total 30981
telemt_desync_full_logged_total 10737
telemt_desync_suppressed_total 20244
telemt_desync_frames_bucket_total{bucket="1_2"} 6263
telemt_desync_frames_bucket_total{bucket="3_10"} 11880
telemt_desync_frames_bucket_total{bucket="gt_10"} 12838
telemt_pool_swap_total 139
telemt_pool_force_close_total 4031
telemt_pool_stale_pick_total 66
telemt_me_writer_close_signal_drop_total 483
telemt_me_draining_writers_reap_progress_total 46549
telemt_me_writer_removed_unexpected_total 1901
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4775
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43702
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3544
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 487
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42518
telemt_me_writer_teardown_success_total{mode="normal"} 48477
telemt_me_writer_teardown_noop_total 46550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95027
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.703611
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95027
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 483
telemt_me_refill_failed_total 4230
telemt_me_writer_restored_same_endpoint_total 1773
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 6130956
telemt_user_connections_current{user="hello"} 4845
telemt_user_octets_from_client{user="hello"} 152322112787 (141.86 GB)
telemt_user_octets_to_client{user="hello"} 2494687348919 (2.27 TB)
telemt_user_msgs_from_client{user="hello"} 115484
telemt_user_msgs_to_client{user="hello"} 517108
telemt_user_unique_ips_current{user="hello"} 2105
telemt_user_unique_ips_recent_window{user="hello"} 622
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 71463.3 (19h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6560160
telemt_connections_bad_total 251577
telemt_connections_current 3667
telemt_connections_me_current 3667
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2658032
telemt_upstream_connect_attempt_total 37658
telemt_upstream_connect_success_total 37389
telemt_upstream_connect_fail_total 262
telemt_upstream_connect_attempts_per_request{bucket="1"} 37651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21944
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15347
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 262
telemt_me_reconnect_attempts_total 47567
telemt_me_reconnect_success_total 1265
telemt_me_reader_eof_total 929
telemt_me_idle_close_by_peer_total 929
telemt_me_route_drop_no_conn_total 1752746
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3262866
telemt_me_endpoint_quarantine_total 493
telemt_me_single_endpoint_outage_enter_total 15
telemt_me_single_endpoint_outage_exit_total 15
telemt_me_single_endpoint_outage_reconnect_attempt_total 54
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 54
telemt_me_single_endpoint_shadow_rotate_total 547
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 17
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
telemt_desync_total 17898
telemt_desync_full_logged_total 6023
telemt_desync_suppressed_total 11875
telemt_desync_frames_bucket_total{bucket="1_2"} 3582
telemt_desync_frames_bucket_total{bucket="3_10"} 6852
telemt_desync_frames_bucket_total{bucket="gt_10"} 7464
telemt_pool_swap_total 76
telemt_pool_force_close_total 2310
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 222
telemt_me_draining_writers_reap_progress_total 25582
telemt_me_writer_removed_unexpected_total 999
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2237
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24367
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1988
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 322
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23272
telemt_me_writer_teardown_success_total{mode="normal"} 26604
telemt_me_writer_teardown_noop_total 25588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52192
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.907367
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52192
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 222
telemt_me_refill_failed_total 2692
telemt_me_writer_restored_same_endpoint_total 1125
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3263083
telemt_user_connections_current{user="hello"} 3667
telemt_user_octets_from_client{user="hello"} 80721249164 (75.18 GB)
telemt_user_octets_to_client{user="hello"} 1385257895050 (1.26 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1349
telemt_user_unique_ips_recent_window{user="hello"} 627
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 52434.8 (14h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 511202
telemt_connections_bad_total 3729
telemt_connections_current 964
telemt_connections_me_current 964
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 9519
telemt_upstream_connect_attempt_total 27647
telemt_upstream_connect_success_total 27584
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 27642
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14425
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 281
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_reconnect_attempts_total 1130
telemt_me_reconnect_success_total 455
telemt_me_reader_eof_total 453
telemt_me_idle_close_by_peer_total 453
telemt_me_route_drop_no_conn_total 166269
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 461965
telemt_me_endpoint_quarantine_total 484
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 449
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 2204
telemt_desync_full_logged_total 645
telemt_desync_suppressed_total 1559
telemt_desync_frames_bucket_total{bucket="1_2"} 657
telemt_desync_frames_bucket_total{bucket="3_10"} 846
telemt_desync_frames_bucket_total{bucket="gt_10"} 701
telemt_pool_swap_total 56
telemt_pool_force_close_total 1327
telemt_me_writer_close_signal_drop_total 65
telemt_me_draining_writers_reap_progress_total 22392
telemt_me_writer_removed_unexpected_total 436
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1642
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21203
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1276
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21065
telemt_me_writer_teardown_success_total{mode="normal"} 22845
telemt_me_writer_teardown_noop_total 22392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45237
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.203503
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45237
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 65
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 402
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 464024
telemt_user_connections_current{user="hello"} 964
telemt_user_octets_from_client{user="hello"} 9263987581 (8.63 GB)
telemt_user_octets_to_client{user="hello"} 226845722935 (211.27 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 341
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 134632.0 (37h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9574386
telemt_connections_bad_total 1118075
telemt_connections_current 5305
telemt_connections_me_current 5305
telemt_handshake_timeouts_total 259530
telemt_upstream_connect_attempt_total 51909
telemt_upstream_connect_success_total 51711
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 51863
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26103
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_reconnect_attempts_total 1933
telemt_me_reconnect_success_total 1060
telemt_me_reader_eof_total 1032
telemt_me_idle_close_by_peer_total 1032
telemt_me_route_drop_no_conn_total 2713798
telemt_me_route_drop_channel_closed_total 70
telemt_me_route_drop_queue_full_total 28
telemt_me_route_drop_queue_full_profile_total{profile="high"} 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7112001
telemt_me_endpoint_quarantine_total 950
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
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
telemt_me_writers_active_current 47
telemt_desync_total 28791
telemt_desync_full_logged_total 9434
telemt_desync_suppressed_total 19357
telemt_desync_frames_bucket_total{bucket="1_2"} 7107
telemt_desync_frames_bucket_total{bucket="3_10"} 10495
telemt_desync_frames_bucket_total{bucket="gt_10"} 11189
telemt_pool_swap_total 149
telemt_pool_force_close_total 4021
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 487
telemt_me_draining_writers_reap_progress_total 46810
telemt_me_writer_removed_unexpected_total 992
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3764
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44069
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3913
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 108
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42789
telemt_me_writer_teardown_success_total{mode="normal"} 47833
telemt_me_writer_teardown_noop_total 46812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94645
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.952214
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94645
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 487
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 931
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 7084468
telemt_user_connections_current{user="hello"} 5305
telemt_user_octets_from_client{user="hello"} 137080976792 (127.67 GB)
telemt_user_octets_to_client{user="hello"} 3310548994992 (3.01 TB)
telemt_user_unique_ips_current{user="hello"} 1948
telemt_user_unique_ips_recent_window{user="hello"} 716
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 134628.4 (37h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8310708
telemt_connections_bad_total 927426
telemt_connections_current 4859
telemt_connections_me_current 4859
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 216597
telemt_upstream_connect_attempt_total 76389
telemt_upstream_connect_success_total 75848
telemt_upstream_connect_fail_total 472
telemt_upstream_connect_attempts_per_request{bucket="1"} 76320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30598
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1967
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 472
telemt_me_reconnect_attempts_total 6562
telemt_me_reconnect_success_total 1524
telemt_me_reader_eof_total 1355
telemt_me_idle_close_by_peer_total 1355
telemt_me_seq_mismatch_total 64
telemt_me_route_drop_no_conn_total 2920353
telemt_me_route_drop_channel_closed_total 258
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6342586
telemt_me_endpoint_quarantine_total 1051
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 34
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 34
telemt_me_single_endpoint_shadow_rotate_total 1020
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
telemt_me_writers_active_current 43
telemt_desync_total 27894
telemt_desync_full_logged_total 9229
telemt_desync_suppressed_total 18665
telemt_desync_frames_bucket_total{bucket="1_2"} 6841
telemt_desync_frames_bucket_total{bucket="3_10"} 10264
telemt_desync_frames_bucket_total{bucket="gt_10"} 10789
telemt_pool_swap_total 146
telemt_pool_force_close_total 3953
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 489
telemt_me_draining_writers_reap_progress_total 45489
telemt_me_writer_removed_unexpected_total 1373
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4415
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42509
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3662
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 291
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41536
telemt_me_writer_teardown_success_total{mode="normal"} 46924
telemt_me_writer_teardown_noop_total 45493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92417
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.496811
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92417
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 489
telemt_me_refill_failed_total 290
telemt_me_writer_restored_same_endpoint_total 1188
telemt_me_writer_restored_fallback_total 88
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 6350906
telemt_user_connections_current{user="hello"} 4859
telemt_user_octets_from_client{user="hello"} 115834226241 (107.88 GB)
telemt_user_octets_to_client{user="hello"} 2700015352835 (2.46 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1881
telemt_user_unique_ips_recent_window{user="hello"} 715
```