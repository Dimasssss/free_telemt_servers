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

# Server Metrics 2026-03-22 12:18:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 54717.9 (15h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1629684
telemt_connections_bad_total 76463
telemt_connections_current 1568
telemt_connections_me_current 1568
telemt_handshake_timeouts_total 72661
telemt_upstream_connect_attempt_total 20815
telemt_upstream_connect_success_total 20814
telemt_upstream_connect_attempts_per_request{bucket="1"} 20814
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7164
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13586
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 774
telemt_me_reconnect_success_total 341
telemt_me_reader_eof_total 338
telemt_me_idle_close_by_peer_total 338
telemt_me_route_drop_no_conn_total 1099050
telemt_me_route_drop_channel_closed_total 493
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1379375
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 387
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 437
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
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
telemt_desync_total 8176
telemt_desync_full_logged_total 2461
telemt_desync_suppressed_total 5715
telemt_desync_frames_bucket_total{bucket="1_2"} 2317
telemt_desync_frames_bucket_total{bucket="3_10"} 3092
telemt_desync_frames_bucket_total{bucket="gt_10"} 2767
telemt_pool_swap_total 60
telemt_pool_force_close_total 1794
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 278
telemt_me_draining_writers_reap_progress_total 18986
telemt_me_writer_removed_unexpected_total 333
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1341
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17850
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1759
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17192
telemt_me_writer_teardown_success_total{mode="normal"} 19191
telemt_me_writer_teardown_noop_total 18988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38179
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 136.204176
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38179
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 278
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 303
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 1376670
telemt_user_connections_current{user="hello"} 1568
telemt_user_octets_from_client{user="hello"} 21506175608 (20.03 GB)
telemt_user_octets_to_client{user="hello"} 408996719972 (380.91 GB)
telemt_user_unique_ips_current{user="hello"} 622
telemt_user_unique_ips_recent_window{user="hello"} 263
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 68084.2 (18h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2640813
telemt_connections_bad_total 238999
telemt_connections_current 2393
telemt_connections_me_current 2393
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 60755
telemt_upstream_connect_attempt_total 45005
telemt_upstream_connect_success_total 44480
telemt_upstream_connect_fail_total 464
telemt_upstream_connect_attempts_per_request{bucket="1"} 44944
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17286
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 117
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 464
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3456
telemt_me_reconnect_success_total 1561
telemt_me_reader_eof_total 1447
telemt_me_idle_close_by_peer_total 1447
telemt_me_route_drop_no_conn_total 2325633
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2072343
telemt_me_endpoint_quarantine_total 573
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 31
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 31
telemt_me_single_endpoint_shadow_rotate_total 534
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_desync_total 8196
telemt_desync_full_logged_total 4621
telemt_desync_suppressed_total 3575
telemt_desync_frames_bucket_total{bucket="1_2"} 1909
telemt_desync_frames_bucket_total{bucket="3_10"} 3187
telemt_desync_frames_bucket_total{bucket="gt_10"} 3100
telemt_pool_swap_total 67
telemt_pool_force_close_total 1890
telemt_me_writer_close_signal_drop_total 158
telemt_me_draining_writers_reap_progress_total 27092
telemt_me_writer_removed_unexpected_total 1407
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2999
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25500
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1680
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 210
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25202
telemt_me_writer_teardown_success_total{mode="normal"} 28499
telemt_me_writer_teardown_noop_total 27092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55591
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.375855
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55591
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 158
telemt_me_refill_failed_total 85
telemt_me_writer_restored_same_endpoint_total 1304
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 2084137
telemt_user_connections_current{user="hello"} 2393
telemt_user_octets_from_client{user="hello"} 25814721735 (24.04 GB)
telemt_user_octets_to_client{user="hello"} 507539773402 (472.68 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1335
telemt_user_unique_ips_recent_window{user="hello"} 720
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 142944.2 (39h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12760878
telemt_connections_bad_total 1113054
telemt_connections_current 5251
telemt_connections_me_current 5251
telemt_handshake_timeouts_total 332002
telemt_upstream_connect_attempt_total 52091
telemt_upstream_connect_success_total 52011
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 52019
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23525
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28262
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 218
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2283
telemt_me_reconnect_success_total 1193
telemt_me_reader_eof_total 1166
telemt_me_idle_close_by_peer_total 1165
telemt_me_route_drop_no_conn_total 10420782
telemt_me_route_drop_channel_closed_total 116
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10198609
telemt_me_endpoint_quarantine_total 902
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1063
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
telemt_me_writers_active_current 44
telemt_desync_total 41845
telemt_desync_full_logged_total 13390
telemt_desync_suppressed_total 28455
telemt_desync_frames_bucket_total{bucket="1_2"} 9444
telemt_desync_frames_bucket_total{bucket="3_10"} 16321
telemt_desync_frames_bucket_total{bucket="gt_10"} 16080
telemt_pool_swap_total 153
telemt_pool_force_close_total 5222
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 824
telemt_me_draining_writers_reap_progress_total 47513
telemt_me_writer_removed_unexpected_total 1125
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4106
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43900
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4812
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 410
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42291
telemt_me_writer_teardown_success_total{mode="normal"} 48006
telemt_me_writer_teardown_noop_total 47561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95567
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 225.581035
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95567
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 824
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 1044
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 10187091
telemt_user_connections_current{user="hello"} 5251
telemt_user_octets_from_client{user="hello"} 150904655496 (140.54 GB)
telemt_user_octets_to_client{user="hello"} 2845042720272 (2.59 TB)
telemt_user_unique_ips_current{user="hello"} 2092
telemt_user_unique_ips_recent_window{user="hello"} 919
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 142945.4 (39h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9649551
telemt_connections_bad_total 879512
telemt_connections_current 4642
telemt_connections_me_current 4642
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 290194
telemt_upstream_connect_attempt_total 78422
telemt_upstream_connect_success_total 77297
telemt_upstream_connect_fail_total 811
telemt_upstream_connect_attempts_per_request{bucket="1"} 78108
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42672
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30799
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 156
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3670
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 811
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3328
telemt_me_reconnect_success_total 1354
telemt_me_reader_eof_total 1238
telemt_me_idle_close_by_peer_total 1238
telemt_me_route_drop_no_conn_total 3872361
telemt_me_route_drop_channel_closed_total 400
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7194450
telemt_me_endpoint_quarantine_total 900
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1089
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
telemt_me_writers_active_current 46
telemt_desync_total 32413
telemt_desync_full_logged_total 10979
telemt_desync_suppressed_total 21434
telemt_desync_frames_bucket_total{bucket="1_2"} 7985
telemt_desync_frames_bucket_total{bucket="3_10"} 12471
telemt_desync_frames_bucket_total{bucket="gt_10"} 11957
telemt_pool_swap_total 153
telemt_pool_force_close_total 4672
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 568
telemt_me_draining_writers_reap_progress_total 45776
telemt_me_writer_removed_unexpected_total 1270
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4077
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42836
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4296
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 376
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41104
telemt_me_writer_teardown_success_total{mode="normal"} 46913
telemt_me_writer_teardown_noop_total 45784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92697
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 82.680356
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92697
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 568
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 1155
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 7135040
telemt_user_connections_current{user="hello"} 4642
telemt_user_octets_from_client{user="hello"} 184288386605 (171.63 GB)
telemt_user_octets_to_client{user="hello"} 3245721231162 (2.95 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 1868
telemt_user_unique_ips_recent_window{user="hello"} 573
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 142911.5 (39h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9107340
telemt_connections_bad_total 764008
telemt_connections_current 4006
telemt_connections_me_current 4006
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 287026
telemt_upstream_connect_attempt_total 62783
telemt_upstream_connect_success_total 62048
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 62195
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29352
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1058
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1423
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3824
telemt_me_reconnect_success_total 1625
telemt_me_reader_eof_total 1494
telemt_me_idle_close_by_peer_total 1494
telemt_me_route_drop_no_conn_total 3967490
telemt_me_route_drop_channel_closed_total 274
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6864459
telemt_me_endpoint_quarantine_total 980
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 20
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 20
telemt_me_single_endpoint_shadow_rotate_total 1045
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
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
telemt_me_writers_active_current 52
telemt_desync_total 32251
telemt_desync_full_logged_total 10783
telemt_desync_suppressed_total 21468
telemt_desync_frames_bucket_total{bucket="1_2"} 8100
telemt_desync_frames_bucket_total{bucket="3_10"} 12384
telemt_desync_frames_bucket_total{bucket="gt_10"} 11767
telemt_pool_swap_total 149
telemt_pool_force_close_total 4633
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 562
telemt_me_draining_writers_reap_progress_total 46570
telemt_me_writer_removed_unexpected_total 1526
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4476
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43542
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 20
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4154
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 479
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41937
telemt_me_writer_teardown_success_total{mode="normal"} 48018
telemt_me_writer_teardown_noop_total 46590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94608
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 68.160338
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94608
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 562
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 1437
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 52
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 6855209
telemt_user_connections_current{user="hello"} 4004
telemt_user_octets_from_client{user="hello"} 166057845023 (154.65 GB)
telemt_user_octets_to_client{user="hello"} 2938768223823 (2.67 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1615
telemt_user_unique_ips_recent_window{user="hello"} 573
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 13189.4 (3h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5583226
telemt_connections_bad_total 334159
telemt_connections_current 6795
telemt_connections_me_current 6795
telemt_relay_adaptive_promotions_total 7
telemt_relay_adaptive_hard_promotions_total 7
telemt_handshake_timeouts_total 88600
telemt_upstream_connect_attempt_total 23921
telemt_upstream_connect_success_total 22853
telemt_upstream_connect_fail_total 836
telemt_upstream_connect_attempts_per_request{bucket="1"} 23689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13153
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4813
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4625
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 836
telemt_me_keepalive_timeout_total 521
telemt_me_reconnect_attempts_total 2295
telemt_me_reconnect_success_total 357
telemt_me_reader_eof_total 228
telemt_me_idle_close_by_peer_total 228
telemt_me_route_drop_no_conn_total 13066926
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 24
telemt_me_route_drop_queue_full_profile_total{profile="high"} 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4676509
telemt_me_endpoint_quarantine_total 86
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 109
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_desync_total 7113
telemt_desync_full_logged_total 1818
telemt_desync_suppressed_total 5295
telemt_desync_frames_bucket_total{bucket="1_2"} 1286
telemt_desync_frames_bucket_total{bucket="3_10"} 2836
telemt_desync_frames_bucket_total{bucket="gt_10"} 2991
telemt_pool_swap_total 12
telemt_pool_force_close_total 505
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 200
telemt_me_draining_writers_reap_progress_total 3437
telemt_me_writer_removed_unexpected_total 316
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 596
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3114
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 364
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 141
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2932
telemt_me_writer_teardown_success_total{mode="normal"} 3710
telemt_me_writer_teardown_noop_total 3440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 5766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 6396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 6671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 6979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 7096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 7149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 7150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 7150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 7150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 7150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 7150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 7150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 7150
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.746226
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 7150
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 200
telemt_me_refill_failed_total 107
telemt_me_writer_restored_same_endpoint_total 242
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 204
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 4690049
telemt_user_connections_current{user="hello"} 6795
telemt_user_octets_from_client{user="hello"} 25970252454 (24.19 GB)
telemt_user_octets_to_client{user="hello"} 136786486175 (127.39 GB)
telemt_user_msgs_from_client{user="hello"} 33078
telemt_user_msgs_to_client{user="hello"} 29827
telemt_user_unique_ips_current{user="hello"} 2458
telemt_user_unique_ips_recent_window{user="hello"} 1235
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 142916.7 (39h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8852679
telemt_connections_bad_total 752624
telemt_connections_current 5257
telemt_connections_me_current 5257
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 187975
telemt_upstream_connect_attempt_total 88206
telemt_upstream_connect_success_total 87336
telemt_upstream_connect_fail_total 748
telemt_upstream_connect_attempts_per_request{bucket="1"} 88084
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54429
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31453
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1246
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 748
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71042
telemt_me_reconnect_success_total 2349
telemt_me_reader_eof_total 2088
telemt_me_idle_close_by_peer_total 2087
telemt_me_route_drop_no_conn_total 4115545
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6988898
telemt_me_endpoint_quarantine_total 947
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 30
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1070
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_me_writers_active_current 128
telemt_desync_total 35719
telemt_desync_full_logged_total 12310
telemt_desync_suppressed_total 23409
telemt_desync_frames_bucket_total{bucket="1_2"} 7293
telemt_desync_frames_bucket_total{bucket="3_10"} 13730
telemt_desync_frames_bucket_total{bucket="gt_10"} 14696
telemt_pool_swap_total 146
telemt_pool_force_close_total 4253
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 516
telemt_me_draining_writers_reap_progress_total 48975
telemt_me_writer_removed_unexpected_total 2117
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5156
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45961
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3708
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 545
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44722
telemt_me_writer_teardown_success_total{mode="normal"} 51117
telemt_me_writer_teardown_noop_total 48976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100093
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.854674
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100093
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 516
telemt_me_refill_failed_total 4241
telemt_me_writer_restored_same_endpoint_total 1972
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 6991713
telemt_user_connections_current{user="hello"} 5257
telemt_user_octets_from_client{user="hello"} 165645536123 (154.27 GB)
telemt_user_octets_to_client{user="hello"} 2709526616221 (2.46 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 2143
telemt_user_unique_ips_recent_window{user="hello"} 650
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 79752.5 (22h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8354094
telemt_connections_bad_total 295573
telemt_connections_current 4001
telemt_connections_me_current 4001
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3498842
telemt_upstream_connect_attempt_total 40434
telemt_upstream_connect_success_total 40144
telemt_upstream_connect_fail_total 283
telemt_upstream_connect_attempts_per_request{bucket="1"} 40427
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16847
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 283
telemt_me_reconnect_attempts_total 47844
telemt_me_reconnect_success_total 1398
telemt_me_reader_eof_total 1068
telemt_me_idle_close_by_peer_total 1068
telemt_me_route_drop_no_conn_total 2856717
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4067217
telemt_me_endpoint_quarantine_total 533
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 57
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 57
telemt_me_single_endpoint_shadow_rotate_total 604
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 20
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
telemt_me_writers_active_current 88
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 22492
telemt_desync_full_logged_total 7495
telemt_desync_suppressed_total 14997
telemt_desync_frames_bucket_total{bucket="1_2"} 4613
telemt_desync_frames_bucket_total{bucket="3_10"} 8739
telemt_desync_frames_bucket_total{bucket="gt_10"} 9140
telemt_pool_swap_total 83
telemt_pool_force_close_total 2550
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 257
telemt_me_draining_writers_reap_progress_total 27935
telemt_me_writer_removed_unexpected_total 1133
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2524
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26572
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2186
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 364
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25385
telemt_me_writer_teardown_success_total{mode="normal"} 29096
telemt_me_writer_teardown_noop_total 27942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57038
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.736548
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57038
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 257
telemt_me_refill_failed_total 2700
telemt_me_writer_restored_same_endpoint_total 1250
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4064058
telemt_user_connections_current{user="hello"} 4001
telemt_user_octets_from_client{user="hello"} 91901001652 (85.59 GB)
telemt_user_octets_to_client{user="hello"} 1600825183326 (1.46 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1645
telemt_user_unique_ips_recent_window{user="hello"} 724
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 60723.0 (16h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 672842
telemt_connections_bad_total 7357
telemt_connections_current 1031
telemt_connections_me_current 1031
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 13207
telemt_upstream_connect_attempt_total 31310
telemt_upstream_connect_success_total 31233
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 31299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14429
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16451
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 353
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_reconnect_attempts_total 1388
telemt_me_reconnect_success_total 598
telemt_me_reader_eof_total 578
telemt_me_idle_close_by_peer_total 578
telemt_me_route_drop_no_conn_total 224720
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 607330
telemt_me_endpoint_quarantine_total 556
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 511
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_desync_total 3333
telemt_desync_full_logged_total 975
telemt_desync_suppressed_total 2358
telemt_desync_frames_bucket_total{bucket="1_2"} 839
telemt_desync_frames_bucket_total{bucket="3_10"} 1320
telemt_desync_frames_bucket_total{bucket="gt_10"} 1174
telemt_pool_swap_total 64
telemt_pool_force_close_total 1569
telemt_me_writer_close_signal_drop_total 86
telemt_me_draining_writers_reap_progress_total 25605
telemt_me_writer_removed_unexpected_total 560
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1944
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24240
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1492
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 77
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24036
telemt_me_writer_teardown_success_total{mode="normal"} 26184
telemt_me_writer_teardown_noop_total 25607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51791
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.785915
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51791
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 86
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 520
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 609096
telemt_user_connections_current{user="hello"} 1031
telemt_user_octets_from_client{user="hello"} 11708749685 (10.90 GB)
telemt_user_octets_to_client{user="hello"} 290202564871 (270.27 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 352
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 142920.6 (39h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10763774
telemt_connections_bad_total 1250952
telemt_connections_current 5793
telemt_connections_me_current 5793
telemt_handshake_timeouts_total 288615
telemt_upstream_connect_attempt_total 54379
telemt_upstream_connect_success_total 54168
telemt_upstream_connect_fail_total 163
telemt_upstream_connect_attempts_per_request{bucket="1"} 54331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26725
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27397
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 163
telemt_me_reconnect_attempts_total 2120
telemt_me_reconnect_success_total 1132
telemt_me_reader_eof_total 1094
telemt_me_idle_close_by_peer_total 1094
telemt_me_route_drop_no_conn_total 3265873
telemt_me_route_drop_channel_closed_total 84
telemt_me_route_drop_queue_full_total 31
telemt_me_route_drop_queue_full_profile_total{profile="high"} 31
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8067434
telemt_me_endpoint_quarantine_total 990
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1074
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
telemt_me_writers_active_current 46
telemt_desync_total 32962
telemt_desync_full_logged_total 10828
telemt_desync_suppressed_total 22134
telemt_desync_frames_bucket_total{bucket="1_2"} 7972
telemt_desync_frames_bucket_total{bucket="3_10"} 12142
telemt_desync_frames_bucket_total{bucket="gt_10"} 12848
telemt_pool_swap_total 158
telemt_pool_force_close_total 4317
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 541
telemt_me_draining_writers_reap_progress_total 49003
telemt_me_writer_removed_unexpected_total 1050
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3994
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46094
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4175
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 142
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44686
telemt_me_writer_teardown_success_total{mode="normal"} 50088
telemt_me_writer_teardown_noop_total 49005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99093
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.405932
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99093
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 541
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 989
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 8038660
telemt_user_connections_current{user="hello"} 5793
telemt_user_octets_from_client{user="hello"} 154657315052 (144.04 GB)
telemt_user_octets_to_client{user="hello"} 3674967535144 (3.34 TB)
telemt_user_unique_ips_current{user="hello"} 1957
telemt_user_unique_ips_recent_window{user="hello"} 831
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 142918.2 (39h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9398480
telemt_connections_bad_total 1060059
telemt_connections_current 5114
telemt_connections_me_current 5114
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 243074
telemt_upstream_connect_attempt_total 79317
telemt_upstream_connect_success_total 78740
telemt_upstream_connect_fail_total 501
telemt_upstream_connect_attempts_per_request{bucket="1"} 79241
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43747
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32098
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1986
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 501
telemt_me_reconnect_attempts_total 6979
telemt_me_reconnect_success_total 1748
telemt_me_reader_eof_total 1576
telemt_me_idle_close_by_peer_total 1576
telemt_me_seq_mismatch_total 69
telemt_me_route_drop_no_conn_total 3899699
telemt_me_route_drop_channel_closed_total 293
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7216672
telemt_me_endpoint_quarantine_total 1096
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1080
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_me_writers_active_current 126
telemt_desync_total 32272
telemt_desync_full_logged_total 10555
telemt_desync_suppressed_total 21717
telemt_desync_frames_bucket_total{bucket="1_2"} 7999
telemt_desync_frames_bucket_total{bucket="3_10"} 12004
telemt_desync_frames_bucket_total{bucket="gt_10"} 12269
telemt_pool_swap_total 153
telemt_pool_force_close_total 4179
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 528
telemt_me_draining_writers_reap_progress_total 47844
telemt_me_writer_removed_unexpected_total 1598
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4793
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44714
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3866
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 313
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43665
telemt_me_writer_teardown_success_total{mode="normal"} 49507
telemt_me_writer_teardown_noop_total 47848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97355
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.195375
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97355
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 528
telemt_me_refill_failed_total 296
telemt_me_writer_restored_same_endpoint_total 1396
telemt_me_writer_restored_fallback_total 93
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 7224558
telemt_user_connections_current{user="hello"} 5114
telemt_user_octets_from_client{user="hello"} 128105176949 (119.31 GB)
telemt_user_octets_to_client{user="hello"} 2907317199447 (2.64 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 2151
telemt_user_unique_ips_recent_window{user="hello"} 628
```