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

# Server Metrics 2026-03-22 04:07:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 25285.6 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 395988
telemt_connections_bad_total 25149
telemt_connections_current 1146
telemt_connections_me_current 1146
telemt_handshake_timeouts_total 21488
telemt_upstream_connect_attempt_total 10625
telemt_upstream_connect_success_total 10624
telemt_upstream_connect_attempts_per_request{bucket="1"} 10624
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6835
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 293
telemt_me_reconnect_success_total 166
telemt_me_reader_eof_total 162
telemt_me_idle_close_by_peer_total 162
telemt_me_route_drop_no_conn_total 81328
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 328286
telemt_me_endpoint_quarantine_total 198
telemt_me_single_endpoint_shadow_rotate_total 211
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
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
telemt_me_writers_warm_current 40
telemt_desync_total 2975
telemt_desync_full_logged_total 813
telemt_desync_suppressed_total 2162
telemt_desync_frames_bucket_total{bucket="1_2"} 1030
telemt_desync_frames_bucket_total{bucket="3_10"} 1120
telemt_desync_frames_bucket_total{bucket="gt_10"} 825
telemt_pool_swap_total 27
telemt_pool_force_close_total 710
telemt_me_writer_close_signal_drop_total 50
telemt_me_draining_writers_reap_progress_total 9550
telemt_me_writer_removed_unexpected_total 160
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 632
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9070
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 705
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8840
telemt_me_writer_teardown_success_total{mode="normal"} 9702
telemt_me_writer_teardown_noop_total 9551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 18698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 19022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 19139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 19215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 19249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 19253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 19253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 19253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 19253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 19253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 19253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 19253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 19253
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.749711
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 19253
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 50
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 149
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 327346
telemt_user_connections_current{user="hello"} 1146
telemt_user_octets_from_client{user="hello"} 4170358244 (3.88 GB)
telemt_user_octets_to_client{user="hello"} 112985239188 (105.23 GB)
telemt_user_unique_ips_current{user="hello"} 437
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 38651.6 (10h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 859557
telemt_connections_bad_total 57367
telemt_connections_current 911
telemt_connections_me_current 911
telemt_handshake_timeouts_total 30938
telemt_upstream_connect_attempt_total 18100
telemt_upstream_connect_success_total 17819
telemt_upstream_connect_fail_total 254
telemt_upstream_connect_attempts_per_request{bucket="1"} 18073
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9934
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 254
telemt_me_reconnect_attempts_total 1501
telemt_me_reconnect_success_total 552
telemt_me_reader_eof_total 489
telemt_me_idle_close_by_peer_total 489
telemt_me_route_drop_no_conn_total 353389
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 680485
telemt_me_endpoint_quarantine_total 362
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 20
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 20
telemt_me_single_endpoint_shadow_rotate_total 312
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_desync_total 2914
telemt_desync_full_logged_total 1668
telemt_desync_suppressed_total 1246
telemt_desync_frames_bucket_total{bucket="1_2"} 614
telemt_desync_frames_bucket_total{bucket="3_10"} 1118
telemt_desync_frames_bucket_total{bucket="gt_10"} 1182
telemt_pool_swap_total 41
telemt_pool_force_close_total 1098
telemt_me_writer_close_signal_drop_total 78
telemt_me_draining_writers_reap_progress_total 16059
telemt_me_writer_removed_unexpected_total 465
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1325
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15210
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1076
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14961
telemt_me_writer_teardown_success_total{mode="normal"} 16535
telemt_me_writer_teardown_noop_total 16059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32594
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.869184
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32594
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 78
telemt_me_refill_failed_total 50
telemt_me_writer_restored_same_endpoint_total 410
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 679452
telemt_user_connections_current{user="hello"} 911
telemt_user_octets_from_client{user="hello"} 11004400624 (10.25 GB)
telemt_user_octets_to_client{user="hello"} 243727359836 (226.99 GB)
telemt_user_unique_ips_current{user="hello"} 589
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 113511.5 (31h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7938342
telemt_connections_bad_total 659837
telemt_connections_current 2555
telemt_connections_me_current 2555
telemt_handshake_timeouts_total 261202
telemt_upstream_connect_attempt_total 42396
telemt_upstream_connect_success_total 42318
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 42326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22980
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 174
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1627
telemt_me_reconnect_success_total 845
telemt_me_reader_eof_total 854
telemt_me_idle_close_by_peer_total 854
telemt_me_route_drop_no_conn_total 4570617
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6412908
telemt_me_endpoint_quarantine_total 737
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 851
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_desync_total 26904
telemt_desync_full_logged_total 8935
telemt_desync_suppressed_total 17969
telemt_desync_frames_bucket_total{bucket="1_2"} 5818
telemt_desync_frames_bucket_total{bucket="3_10"} 10508
telemt_desync_frames_bucket_total{bucket="gt_10"} 10578
telemt_pool_swap_total 123
telemt_pool_force_close_total 4018
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 613
telemt_me_draining_writers_reap_progress_total 38667
telemt_me_writer_removed_unexpected_total 822
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3212
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35812
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3778
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 240
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34649
telemt_me_writer_teardown_success_total{mode="normal"} 39024
telemt_me_writer_teardown_noop_total 38711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77735
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 162.429913
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77735
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 613
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 753
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 6404780
telemt_user_connections_current{user="hello"} 2555
telemt_user_octets_from_client{user="hello"} 108979976724 (101.50 GB)
telemt_user_octets_to_client{user="hello"} 2150468420116 (1.96 TB)
telemt_user_unique_ips_current{user="hello"} 1212
telemt_user_unique_ips_recent_window{user="hello"} 308
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 113512.8 (31h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6566886
telemt_connections_bad_total 593771
telemt_connections_current 2354
telemt_connections_me_current 2354
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 218111
telemt_upstream_connect_attempt_total 46341
telemt_upstream_connect_success_total 45945
telemt_upstream_connect_fail_total 199
telemt_upstream_connect_attempts_per_request{bucket="1"} 46144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22736
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22619
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 557
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 199
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1971
telemt_me_reconnect_success_total 901
telemt_me_reader_eof_total 875
telemt_me_idle_close_by_peer_total 875
telemt_me_route_drop_no_conn_total 2285809
telemt_me_route_drop_channel_closed_total 277
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4899703
telemt_me_endpoint_quarantine_total 719
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 875
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
telemt_me_writers_active_current 43
telemt_desync_total 22972
telemt_desync_full_logged_total 7840
telemt_desync_suppressed_total 15132
telemt_desync_frames_bucket_total{bucket="1_2"} 5523
telemt_desync_frames_bucket_total{bucket="3_10"} 8924
telemt_desync_frames_bucket_total{bucket="gt_10"} 8525
telemt_pool_swap_total 124
telemt_pool_force_close_total 3650
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 371
telemt_me_draining_writers_reap_progress_total 37116
telemt_me_writer_removed_unexpected_total 857
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3069
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34844
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3433
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 217
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33466
telemt_me_writer_teardown_success_total{mode="normal"} 37913
telemt_me_writer_teardown_noop_total 37122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75035
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.499482
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75035
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 371
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 788
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 4821437
telemt_user_connections_current{user="hello"} 2354
telemt_user_octets_from_client{user="hello"} 142928585221 (133.11 GB)
telemt_user_octets_to_client{user="hello"} 2291520441983 (2.08 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1070
telemt_user_unique_ips_recent_window{user="hello"} 278
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 113479.3 (31h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6434585
telemt_connections_bad_total 551744
telemt_connections_current 1760
telemt_connections_me_current 1760
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 211242
telemt_upstream_connect_attempt_total 52784
telemt_upstream_connect_success_total 52302
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 52444
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24194
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 613
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 2258
telemt_me_reconnect_success_total 1012
telemt_me_reader_eof_total 950
telemt_me_idle_close_by_peer_total 950
telemt_me_route_drop_no_conn_total 2233487
telemt_me_route_drop_channel_closed_total 128
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4781010
telemt_me_endpoint_quarantine_total 795
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 846
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_me_writers_active_current 90
telemt_me_writers_warm_current 25
telemt_desync_total 22882
telemt_desync_full_logged_total 7725
telemt_desync_suppressed_total 15157
telemt_desync_frames_bucket_total{bucket="1_2"} 5588
telemt_desync_frames_bucket_total{bucket="3_10"} 8772
telemt_desync_frames_bucket_total{bucket="gt_10"} 8522
telemt_pool_swap_total 121
telemt_pool_force_close_total 3507
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 400
telemt_me_draining_writers_reap_progress_total 38273
telemt_me_writer_removed_unexpected_total 937
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3231
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35996
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3292
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34766
telemt_me_writer_teardown_success_total{mode="normal"} 39227
telemt_me_writer_teardown_noop_total 38285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77512
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 29.188621
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77512
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 400
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 886
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 4776183
telemt_user_connections_current{user="hello"} 1760
telemt_user_octets_from_client{user="hello"} 135291061307 (126.00 GB)
telemt_user_octets_to_client{user="hello"} 2187066120635 (1.99 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 852
telemt_user_unique_ips_recent_window{user="hello"} 255
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 113516.0 (31h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20709435
telemt_connections_bad_total 1708325
telemt_connections_current 3064
telemt_connections_me_current 3064
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 625395
telemt_upstream_connect_attempt_total 203184
telemt_upstream_connect_success_total 184893
telemt_upstream_connect_fail_total 16470
telemt_upstream_connect_attempts_per_request{bucket="1"} 201363
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 130297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44422
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8950
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16470
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65149
telemt_me_reconnect_success_total 2415
telemt_me_reader_eof_total 1499
telemt_me_idle_close_by_peer_total 1498
telemt_me_route_drop_no_conn_total 39569319
telemt_me_route_drop_channel_closed_total 127
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16679897
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 886
telemt_me_single_endpoint_outage_enter_total 144
telemt_me_single_endpoint_outage_exit_total 144
telemt_me_single_endpoint_outage_reconnect_attempt_total 297
telemt_me_single_endpoint_outage_reconnect_success_total 76
telemt_me_single_endpoint_quarantine_bypass_total 297
telemt_me_single_endpoint_shadow_rotate_total 892
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
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
telemt_desync_total 32290
telemt_desync_full_logged_total 9720
telemt_desync_suppressed_total 22570
telemt_desync_frames_bucket_total{bucket="1_2"} 7013
telemt_desync_frames_bucket_total{bucket="3_10"} 14319
telemt_desync_frames_bucket_total{bucket="gt_10"} 10958
telemt_pool_swap_total 118
telemt_pool_force_close_total 3775
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 831
telemt_me_draining_writers_reap_progress_total 35612
telemt_me_writer_removed_unexpected_total 2240
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4802
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32793
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3244
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 531
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31837
telemt_me_writer_teardown_success_total{mode="normal"} 37595
telemt_me_writer_teardown_noop_total 35639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73234
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 216.557100
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73234
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 831
telemt_me_refill_failed_total 3808
telemt_me_writer_restored_same_endpoint_total 1640
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 579
telemt_user_connections_total{user="hello"} 16814669
telemt_user_connections_current{user="hello"} 3064
telemt_user_octets_from_client{user="hello"} 235442418884 (219.27 GB)
telemt_user_octets_to_client{user="hello"} 1264039719927 (1.15 TB)
telemt_user_msgs_from_client{user="hello"} 398569
telemt_user_msgs_to_client{user="hello"} 788102
telemt_user_unique_ips_current{user="hello"} 1337
telemt_user_unique_ips_recent_window{user="hello"} 397
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 113483.4 (31h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6205621
telemt_connections_bad_total 600840
telemt_connections_current 2137
telemt_connections_me_current 2137
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 130645
telemt_upstream_connect_attempt_total 61139
telemt_upstream_connect_success_total 60442
telemt_upstream_connect_fail_total 595
telemt_upstream_connect_attempts_per_request{bucket="1"} 61037
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25046
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 356
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 595
telemt_me_reconnect_attempts_total 69764
telemt_me_reconnect_success_total 1826
telemt_me_reader_eof_total 1609
telemt_me_idle_close_by_peer_total 1608
telemt_me_route_drop_no_conn_total 2416732
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4814124
telemt_me_endpoint_quarantine_total 768
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 860
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 32
telemt_desync_total 24068
telemt_desync_full_logged_total 8438
telemt_desync_suppressed_total 15630
telemt_desync_frames_bucket_total{bucket="1_2"} 4701
telemt_desync_frames_bucket_total{bucket="3_10"} 9304
telemt_desync_frames_bucket_total{bucket="gt_10"} 10063
telemt_pool_swap_total 117
telemt_pool_force_close_total 3344
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 402
telemt_me_draining_writers_reap_progress_total 40104
telemt_me_writer_removed_unexpected_total 1646
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4072
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37710
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2943
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36760
telemt_me_writer_teardown_success_total{mode="normal"} 41782
telemt_me_writer_teardown_noop_total 40105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81887
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.267660
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81887
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 402
telemt_me_refill_failed_total 4210
telemt_me_writer_restored_same_endpoint_total 1534
telemt_me_writer_restored_fallback_total 35
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 4806589
telemt_user_connections_current{user="hello"} 2137
telemt_user_octets_from_client{user="hello"} 126460650468 (117.78 GB)
telemt_user_octets_to_client{user="hello"} 1975282009414 (1.80 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1012
telemt_user_unique_ips_recent_window{user="hello"} 272
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 50319.3 (13h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4145096
telemt_connections_bad_total 176073
telemt_connections_current 1761
telemt_connections_me_current 1761
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1666290
telemt_upstream_connect_attempt_total 29970
telemt_upstream_connect_success_total 29774
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 29963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11338
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_reconnect_attempts_total 45967
telemt_me_reconnect_success_total 1004
telemt_me_reader_eof_total 690
telemt_me_idle_close_by_peer_total 690
telemt_me_route_drop_no_conn_total 1044783
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2028332
telemt_me_endpoint_quarantine_total 372
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 390
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
telemt_me_writers_active_current 47
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10866
telemt_desync_full_logged_total 3763
telemt_desync_suppressed_total 7103
telemt_desync_frames_bucket_total{bucket="1_2"} 1994
telemt_desync_frames_bucket_total{bucket="3_10"} 4174
telemt_desync_frames_bucket_total{bucket="gt_10"} 4698
telemt_pool_swap_total 54
telemt_pool_force_close_total 1593
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 145
telemt_me_draining_writers_reap_progress_total 18786
telemt_me_writer_removed_unexpected_total 763
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1642
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17934
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1387
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17193
telemt_me_writer_teardown_success_total{mode="normal"} 19576
telemt_me_writer_teardown_noop_total 18788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38364
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.508563
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38364
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 145
telemt_me_refill_failed_total 2612
telemt_me_writer_restored_same_endpoint_total 897
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2031799
telemt_user_connections_current{user="hello"} 1761
telemt_user_octets_from_client{user="hello"} 55662450516 (51.84 GB)
telemt_user_octets_to_client{user="hello"} 867620762334 (808.03 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 869
telemt_user_unique_ips_recent_window{user="hello"} 271
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 31290.4 (8h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221676
telemt_connections_bad_total 1817
telemt_connections_current 375
telemt_connections_me_current 375
telemt_handshake_timeouts_total 5912
telemt_upstream_connect_attempt_total 15164
telemt_upstream_connect_success_total 15128
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 15162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8640
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_reconnect_attempts_total 343
telemt_me_reconnect_success_total 200
telemt_me_reader_eof_total 204
telemt_me_idle_close_by_peer_total 204
telemt_me_route_drop_no_conn_total 61358
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 196099
telemt_me_endpoint_quarantine_total 300
telemt_me_single_endpoint_shadow_rotate_total 272
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_me_writers_active_current 45
telemt_desync_total 1123
telemt_desync_full_logged_total 295
telemt_desync_suppressed_total 828
telemt_desync_frames_bucket_total{bucket="1_2"} 413
telemt_desync_frames_bucket_total{bucket="3_10"} 422
telemt_desync_frames_bucket_total{bucket="gt_10"} 288
telemt_pool_swap_total 34
telemt_pool_force_close_total 758
telemt_me_writer_close_signal_drop_total 25
telemt_me_draining_writers_reap_progress_total 13711
telemt_me_writer_removed_unexpected_total 197
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 866
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13049
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 756
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12953
telemt_me_writer_teardown_success_total{mode="normal"} 13915
telemt_me_writer_teardown_noop_total 13711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27626
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.091768
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27626
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 25
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 181
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 195763
telemt_user_connections_current{user="hello"} 375
telemt_user_octets_from_client{user="hello"} 3375315132 (3.14 GB)
telemt_user_octets_to_client{user="hello"} 118910378712 (110.74 GB)
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 113488.0 (31h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7519962
telemt_connections_bad_total 757134
telemt_connections_current 2230
telemt_connections_me_current 2230
telemt_handshake_timeouts_total 214758
telemt_upstream_connect_attempt_total 44760
telemt_upstream_connect_success_total 44597
telemt_upstream_connect_fail_total 126
telemt_upstream_connect_attempts_per_request{bucket="1"} 44723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22078
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22478
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 126
telemt_me_reconnect_attempts_total 1641
telemt_me_reconnect_success_total 874
telemt_me_reader_eof_total 861
telemt_me_idle_close_by_peer_total 861
telemt_me_route_drop_no_conn_total 2154481
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5604486
telemt_me_endpoint_quarantine_total 806
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 872
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_me_writers_warm_current 35
telemt_desync_total 21974
telemt_desync_full_logged_total 7216
telemt_desync_suppressed_total 14758
telemt_desync_frames_bucket_total{bucket="1_2"} 5508
telemt_desync_frames_bucket_total{bucket="3_10"} 7964
telemt_desync_frames_bucket_total{bucket="gt_10"} 8502
telemt_pool_swap_total 125
telemt_pool_force_close_total 3335
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 397
telemt_me_draining_writers_reap_progress_total 40365
telemt_me_writer_removed_unexpected_total 829
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3137
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38079
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3247
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37030
telemt_me_writer_teardown_success_total{mode="normal"} 41216
telemt_me_writer_teardown_noop_total 40367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81583
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.721155
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81583
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 397
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 782
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 5579373
telemt_user_connections_current{user="hello"} 2230
telemt_user_octets_from_client{user="hello"} 111108520468 (103.48 GB)
telemt_user_octets_to_client{user="hello"} 2600449567240 (2.37 TB)
telemt_user_unique_ips_current{user="hello"} 994
telemt_user_unique_ips_recent_window{user="hello"} 248
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 113484.4 (31h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6516344
telemt_connections_bad_total 639072
telemt_connections_current 2067
telemt_connections_me_current 2067
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 175958
telemt_upstream_connect_attempt_total 60552
telemt_upstream_connect_success_total 60097
telemt_upstream_connect_fail_total 395
telemt_upstream_connect_attempts_per_request{bucket="1"} 60492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24105
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 395
telemt_me_reconnect_attempts_total 5620
telemt_me_reconnect_success_total 1218
telemt_me_reader_eof_total 1101
telemt_me_idle_close_by_peer_total 1101
telemt_me_seq_mismatch_total 52
telemt_me_route_drop_no_conn_total 2206731
telemt_me_route_drop_channel_closed_total 191
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4971373
telemt_me_endpoint_quarantine_total 888
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 868
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_me_writers_warm_current 27
telemt_desync_total 20566
telemt_desync_full_logged_total 6868
telemt_desync_suppressed_total 13698
telemt_desync_frames_bucket_total{bucket="1_2"} 5251
telemt_desync_frames_bucket_total{bucket="3_10"} 7519
telemt_desync_frames_bucket_total{bucket="gt_10"} 7796
telemt_pool_swap_total 123
telemt_pool_force_close_total 3286
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 390
telemt_me_draining_writers_reap_progress_total 38911
telemt_me_writer_removed_unexpected_total 1113
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3687
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36392
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3063
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35625
telemt_me_writer_teardown_success_total{mode="normal"} 40079
telemt_me_writer_teardown_noop_total 38915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78994
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.199464
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78994
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 390
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 953
telemt_me_writer_restored_fallback_total 70
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 4974230
telemt_user_connections_current{user="hello"} 2067
telemt_user_octets_from_client{user="hello"} 93913800857 (87.46 GB)
telemt_user_octets_to_client{user="hello"} 2127593941500 (1.94 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 931
telemt_user_unique_ips_recent_window{user="hello"} 297
```