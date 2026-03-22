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

# Server Metrics 2026-03-22 11:42:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 52565.8 (14h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1512880
telemt_connections_bad_total 73355
telemt_connections_current 1804
telemt_connections_me_current 1804
telemt_handshake_timeouts_total 68960
telemt_upstream_connect_attempt_total 20185
telemt_upstream_connect_success_total 20184
telemt_upstream_connect_attempts_per_request{bucket="1"} 20184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6952
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13170
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 50
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 746
telemt_me_reconnect_success_total 334
telemt_me_reader_eof_total 333
telemt_me_idle_close_by_peer_total 333
telemt_me_route_drop_no_conn_total 979040
telemt_me_route_drop_channel_closed_total 453
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1275981
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 375
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 424
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
telemt_me_writers_active_current 39
telemt_desync_total 7866
telemt_desync_full_logged_total 2348
telemt_desync_suppressed_total 5518
telemt_desync_frames_bucket_total{bucket="1_2"} 2255
telemt_desync_frames_bucket_total{bucket="3_10"} 2949
telemt_desync_frames_bucket_total{bucket="gt_10"} 2662
telemt_pool_swap_total 58
telemt_pool_force_close_total 1731
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 265
telemt_me_draining_writers_reap_progress_total 18411
telemt_me_writer_removed_unexpected_total 328
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1295
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17322
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1696
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16680
telemt_me_writer_teardown_success_total{mode="normal"} 18617
telemt_me_writer_teardown_noop_total 18413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37030
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 127.235567
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37030
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 265
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 299
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 1273470
telemt_user_connections_current{user="hello"} 1804
telemt_user_octets_from_client{user="hello"} 20221336184 (18.83 GB)
telemt_user_octets_to_client{user="hello"} 385729223864 (359.24 GB)
telemt_user_unique_ips_current{user="hello"} 657
telemt_user_unique_ips_recent_window{user="hello"} 287
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 65932.3 (18h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2467211
telemt_connections_bad_total 211492
telemt_connections_current 1346
telemt_connections_me_current 1346
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 56425
telemt_upstream_connect_attempt_total 44115
telemt_upstream_connect_success_total 43600
telemt_upstream_connect_fail_total 455
telemt_upstream_connect_attempts_per_request{bucket="1"} 44055
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16787
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 455
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3391
telemt_me_reconnect_success_total 1506
telemt_me_reader_eof_total 1391
telemt_me_idle_close_by_peer_total 1391
telemt_me_route_drop_no_conn_total 2131614
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1942690
telemt_me_endpoint_quarantine_total 569
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 30
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 519
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
telemt_me_writers_active_current 41
telemt_desync_total 7696
telemt_desync_full_logged_total 4343
telemt_desync_suppressed_total 3353
telemt_desync_frames_bucket_total{bucket="1_2"} 1773
telemt_desync_frames_bucket_total{bucket="3_10"} 3012
telemt_desync_frames_bucket_total{bucket="gt_10"} 2911
telemt_pool_swap_total 66
telemt_pool_force_close_total 1865
telemt_me_writer_close_signal_drop_total 155
telemt_me_draining_writers_reap_progress_total 26393
telemt_me_writer_removed_unexpected_total 1353
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2911
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24833
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1655
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 210
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24528
telemt_me_writer_teardown_success_total{mode="normal"} 27744
telemt_me_writer_teardown_noop_total 26393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54137
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.111261
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54137
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 155
telemt_me_refill_failed_total 85
telemt_me_writer_restored_same_endpoint_total 1253
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 1954518
telemt_user_connections_current{user="hello"} 1346
telemt_user_octets_from_client{user="hello"} 24531768435 (22.85 GB)
telemt_user_octets_to_client{user="hello"} 488082041002 (454.56 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 817
telemt_user_unique_ips_recent_window{user="hello"} 772
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 140792.0 (39h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12392724
telemt_connections_bad_total 1074067
telemt_connections_current 5084
telemt_connections_me_current 5084
telemt_handshake_timeouts_total 323869
telemt_upstream_connect_attempt_total 51190
telemt_upstream_connect_success_total 51110
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 51118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23142
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27750
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2209
telemt_me_reconnect_success_total 1137
telemt_me_reader_eof_total 1107
telemt_me_idle_close_by_peer_total 1106
telemt_me_route_drop_no_conn_total 9992997
telemt_me_route_drop_channel_closed_total 108
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9898483
telemt_me_endpoint_quarantine_total 893
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1050
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
telemt_me_writers_active_current 50
telemt_desync_total 40572
telemt_desync_full_logged_total 13012
telemt_desync_suppressed_total 27560
telemt_desync_frames_bucket_total{bucket="1_2"} 9124
telemt_desync_frames_bucket_total{bucket="3_10"} 15849
telemt_desync_frames_bucket_total{bucket="gt_10"} 15599
telemt_pool_swap_total 152
telemt_pool_force_close_total 5130
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 803
telemt_me_draining_writers_reap_progress_total 46692
telemt_me_writer_removed_unexpected_total 1067
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4011
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43143
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4787
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 343
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41562
telemt_me_writer_teardown_success_total{mode="normal"} 47154
telemt_me_writer_teardown_noop_total 46736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93890
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 218.548137
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93890
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 803
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 988
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 9887401
telemt_user_connections_current{user="hello"} 5084
telemt_user_octets_from_client{user="hello"} 146839371988 (136.75 GB)
telemt_user_octets_to_client{user="hello"} 2788763787860 (2.54 TB)
telemt_user_unique_ips_current{user="hello"} 1944
telemt_user_unique_ips_recent_window{user="hello"} 1037
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 140793.6 (39h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9321168
telemt_connections_bad_total 837501
telemt_connections_current 4080
telemt_connections_me_current 4080
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 283873
telemt_upstream_connect_attempt_total 57749
telemt_upstream_connect_success_total 57168
telemt_upstream_connect_fail_total 267
telemt_upstream_connect_attempts_per_request{bucket="1"} 57435
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28105
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 131
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 267
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3259
telemt_me_reconnect_success_total 1323
telemt_me_reader_eof_total 1209
telemt_me_idle_close_by_peer_total 1209
telemt_me_route_drop_no_conn_total 3774182
telemt_me_route_drop_channel_closed_total 384
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6957184
telemt_me_endpoint_quarantine_total 888
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1077
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
telemt_me_writers_active_current 45
telemt_desync_total 31584
telemt_desync_full_logged_total 10671
telemt_desync_suppressed_total 20913
telemt_desync_frames_bucket_total{bucket="1_2"} 7788
telemt_desync_frames_bucket_total{bucket="3_10"} 12152
telemt_desync_frames_bucket_total{bucket="gt_10"} 11644
telemt_pool_swap_total 151
telemt_pool_force_close_total 4633
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 541
telemt_me_draining_writers_reap_progress_total 45196
telemt_me_writer_removed_unexpected_total 1242
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4004
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42328
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4265
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 368
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40563
telemt_me_writer_teardown_success_total{mode="normal"} 46332
telemt_me_writer_teardown_noop_total 45204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91536
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 71.492799
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91536
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 541
telemt_me_refill_failed_total 105
telemt_me_writer_restored_same_endpoint_total 1131
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 6878419
telemt_user_connections_current{user="hello"} 4080
telemt_user_octets_from_client{user="hello"} 180013399471 (167.65 GB)
telemt_user_octets_to_client{user="hello"} 3162630316802 (2.88 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1622
telemt_user_unique_ips_recent_window{user="hello"} 676
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 140758.1 (39h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8839104
telemt_connections_bad_total 740117
telemt_connections_current 4688
telemt_connections_me_current 4688
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 281218
telemt_upstream_connect_attempt_total 62011
telemt_upstream_connect_success_total 61292
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 61439
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28955
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1034
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1405
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3773
telemt_me_reconnect_success_total 1586
telemt_me_reader_eof_total 1471
telemt_me_idle_close_by_peer_total 1471
telemt_me_route_drop_no_conn_total 3756402
telemt_me_route_drop_channel_closed_total 253
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6647433
telemt_me_endpoint_quarantine_total 961
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 1028
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
telemt_me_writers_active_current 86
telemt_desync_total 30829
telemt_desync_full_logged_total 10414
telemt_desync_suppressed_total 20415
telemt_desync_frames_bucket_total{bucket="1_2"} 7582
telemt_desync_frames_bucket_total{bucket="3_10"} 11881
telemt_desync_frames_bucket_total{bucket="gt_10"} 11366
telemt_pool_swap_total 147
telemt_pool_force_close_total 4522
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 539
telemt_me_draining_writers_reap_progress_total 45857
telemt_me_writer_removed_unexpected_total 1502
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4394
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42903
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4087
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 435
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41335
telemt_me_writer_teardown_success_total{mode="normal"} 47297
telemt_me_writer_teardown_noop_total 45874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93171
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 57.098658
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93171
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 539
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 1405
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 6638619
telemt_user_connections_current{user="hello"} 4688
telemt_user_octets_from_client{user="hello"} 163107325183 (151.91 GB)
telemt_user_octets_to_client{user="hello"} 2874393103163 (2.61 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1891
telemt_user_unique_ips_recent_window{user="hello"} 621
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 11037.3 (3h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4699260
telemt_connections_bad_total 292026
telemt_connections_current 6524
telemt_connections_me_current 6524
telemt_relay_adaptive_promotions_total 7
telemt_relay_adaptive_hard_promotions_total 7
telemt_handshake_timeouts_total 73901
telemt_upstream_connect_attempt_total 23288
telemt_upstream_connect_success_total 22245
telemt_upstream_connect_fail_total 832
telemt_upstream_connect_attempts_per_request{bucket="1"} 23077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4476
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4620
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 832
telemt_me_keepalive_timeout_total 470
telemt_me_reconnect_attempts_total 2270
telemt_me_reconnect_success_total 337
telemt_me_reader_eof_total 208
telemt_me_idle_close_by_peer_total 208
telemt_me_route_drop_no_conn_total 10798719
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3926859
telemt_me_endpoint_quarantine_total 78
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 93
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
telemt_desync_total 5699
telemt_desync_full_logged_total 1486
telemt_desync_suppressed_total 4213
telemt_desync_frames_bucket_total{bucket="1_2"} 1068
telemt_desync_frames_bucket_total{bucket="3_10"} 2295
telemt_desync_frames_bucket_total{bucket="gt_10"} 2336
telemt_pool_swap_total 10
telemt_pool_force_close_total 435
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 179
telemt_me_draining_writers_reap_progress_total 2910
telemt_me_writer_removed_unexpected_total 297
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 543
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2627
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 301
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 134
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2475
telemt_me_writer_teardown_success_total{mode="normal"} 3170
telemt_me_writer_teardown_noop_total 2913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 5458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 5700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 5949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 6048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 6082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 6083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 6083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 6083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 6083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 6083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 6083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 6083
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.442907
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 6083
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 179
telemt_me_refill_failed_total 107
telemt_me_writer_restored_same_endpoint_total 223
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 204
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 3942100
telemt_user_connections_current{user="hello"} 6524
telemt_user_octets_from_client{user="hello"} 21249082566 (19.79 GB)
telemt_user_octets_to_client{user="hello"} 114916912255 (107.02 GB)
telemt_user_msgs_from_client{user="hello"} 33078
telemt_user_msgs_to_client{user="hello"} 29827
telemt_user_unique_ips_current{user="hello"} 2322
telemt_user_unique_ips_recent_window{user="hello"} 1419
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 140764.0 (39h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8590473
telemt_connections_bad_total 739376
telemt_connections_current 5018
telemt_connections_me_current 5018
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 179855
telemt_upstream_connect_attempt_total 87227
telemt_upstream_connect_success_total 86361
telemt_upstream_connect_fail_total 745
telemt_upstream_connect_attempts_per_request{bucket="1"} 87106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30936
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 745
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70713
telemt_me_reconnect_success_total 2214
telemt_me_reader_eof_total 1944
telemt_me_idle_close_by_peer_total 1943
telemt_me_route_drop_no_conn_total 3875756
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6784827
telemt_me_endpoint_quarantine_total 945
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 30
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1057
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
telemt_me_writers_active_current 47
telemt_desync_total 34639
telemt_desync_full_logged_total 11919
telemt_desync_suppressed_total 22720
telemt_desync_frames_bucket_total{bucket="1_2"} 7096
telemt_desync_frames_bucket_total{bucket="3_10"} 13284
telemt_desync_frames_bucket_total{bucket="gt_10"} 14259
telemt_pool_swap_total 146
telemt_pool_force_close_total 4253
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 514
telemt_me_draining_writers_reap_progress_total 48275
telemt_me_writer_removed_unexpected_total 1973
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4984
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45289
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3708
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 545
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44022
telemt_me_writer_teardown_success_total{mode="normal"} 50273
telemt_me_writer_teardown_noop_total 48276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98549
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.842943
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98549
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 514
telemt_me_refill_failed_total 4235
telemt_me_writer_restored_same_endpoint_total 1837
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 6787697
telemt_user_connections_current{user="hello"} 5018
telemt_user_octets_from_client{user="hello"} 162045227783 (150.92 GB)
telemt_user_octets_to_client{user="hello"} 2653229265873 (2.41 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 1972
telemt_user_unique_ips_recent_window{user="hello"} 1060
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 77599.9 (21h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7861662
telemt_connections_bad_total 286103
telemt_connections_current 3749
telemt_connections_me_current 3749
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3258669
telemt_upstream_connect_attempt_total 39687
telemt_upstream_connect_success_total 39400
telemt_upstream_connect_fail_total 280
telemt_upstream_connect_attempts_per_request{bucket="1"} 39680
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16424
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 280
telemt_me_reconnect_attempts_total 47790
telemt_me_reconnect_success_total 1345
telemt_me_reader_eof_total 1013
telemt_me_idle_close_by_peer_total 1013
telemt_me_route_drop_no_conn_total 2546888
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3859776
telemt_me_endpoint_quarantine_total 527
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 57
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 57
telemt_me_single_endpoint_shadow_rotate_total 591
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
telemt_me_writers_active_current 44
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 21146
telemt_desync_full_logged_total 7078
telemt_desync_suppressed_total 14068
telemt_desync_frames_bucket_total{bucket="1_2"} 4337
telemt_desync_frames_bucket_total{bucket="3_10"} 8185
telemt_desync_frames_bucket_total{bucket="gt_10"} 8624
telemt_pool_swap_total 82
telemt_pool_force_close_total 2520
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 252
telemt_me_draining_writers_reap_progress_total 27362
telemt_me_writer_removed_unexpected_total 1080
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2440
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26028
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2157
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 363
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24842
telemt_me_writer_teardown_success_total{mode="normal"} 28468
telemt_me_writer_teardown_noop_total 27369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55837
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.680678
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55837
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 252
telemt_me_refill_failed_total 2700
telemt_me_writer_restored_same_endpoint_total 1197
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3857512
telemt_user_connections_current{user="hello"} 3749
telemt_user_octets_from_client{user="hello"} 89186780252 (83.06 GB)
telemt_user_octets_to_client{user="hello"} 1545587829310 (1.41 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1313
telemt_user_unique_ips_recent_window{user="hello"} 1258
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 58571.1 (16h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 630624
telemt_connections_bad_total 6108
telemt_connections_current 973
telemt_connections_me_current 973
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 12224
telemt_upstream_connect_attempt_total 30361
telemt_upstream_connect_success_total 30292
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 30353
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14022
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15936
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 334
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_reconnect_attempts_total 1336
telemt_me_reconnect_success_total 571
telemt_me_reader_eof_total 556
telemt_me_idle_close_by_peer_total 556
telemt_me_route_drop_no_conn_total 209921
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 569295
telemt_me_endpoint_quarantine_total 530
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 491
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 30
telemt_desync_total 3149
telemt_desync_full_logged_total 909
telemt_desync_suppressed_total 2240
telemt_desync_frames_bucket_total{bucket="1_2"} 818
telemt_desync_frames_bucket_total{bucket="3_10"} 1231
telemt_desync_frames_bucket_total{bucket="gt_10"} 1100
telemt_pool_swap_total 61
telemt_pool_force_close_total 1490
telemt_me_writer_close_signal_drop_total 79
telemt_me_draining_writers_reap_progress_total 24719
telemt_me_writer_removed_unexpected_total 538
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1852
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23424
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1414
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 76
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23229
telemt_me_writer_teardown_success_total{mode="normal"} 25276
telemt_me_writer_teardown_noop_total 24719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49995
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.692297
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49995
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 79
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 501
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 571181
telemt_user_connections_current{user="hello"} 973
telemt_user_octets_from_client{user="hello"} 10849631573 (10.10 GB)
telemt_user_octets_to_client{user="hello"} 267314245735 (248.96 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 352
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 140768.5 (39h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10397391
telemt_connections_bad_total 1215030
telemt_connections_current 5792
telemt_connections_me_current 5792
telemt_handshake_timeouts_total 274983
telemt_upstream_connect_attempt_total 53702
telemt_upstream_connect_success_total 53497
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 53655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27048
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_reconnect_attempts_total 2093
telemt_me_reconnect_success_total 1105
telemt_me_reader_eof_total 1072
telemt_me_idle_close_by_peer_total 1072
telemt_me_route_drop_no_conn_total 3037418
telemt_me_route_drop_channel_closed_total 83
telemt_me_route_drop_queue_full_total 30
telemt_me_route_drop_queue_full_profile_total{profile="high"} 30
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7771753
telemt_me_endpoint_quarantine_total 980
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1060
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
telemt_desync_total 31778
telemt_desync_full_logged_total 10444
telemt_desync_suppressed_total 21334
telemt_desync_frames_bucket_total{bucket="1_2"} 7696
telemt_desync_frames_bucket_total{bucket="3_10"} 11672
telemt_desync_frames_bucket_total{bucket="gt_10"} 12410
telemt_pool_swap_total 156
telemt_pool_force_close_total 4250
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 521
telemt_me_draining_writers_reap_progress_total 48438
telemt_me_writer_removed_unexpected_total 1029
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3931
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45570
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4116
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 134
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44188
telemt_me_writer_teardown_success_total{mode="normal"} 49501
telemt_me_writer_teardown_noop_total 48440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97941
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.016190
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97941
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 521
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 964
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 7743120
telemt_user_connections_current{user="hello"} 5792
telemt_user_octets_from_client{user="hello"} 150169069752 (139.86 GB)
telemt_user_octets_to_client{user="hello"} 3585858547760 (3.26 TB)
telemt_user_unique_ips_current{user="hello"} 2111
telemt_user_unique_ips_recent_window{user="hello"} 682
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 140765.1 (39h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9103554
telemt_connections_bad_total 1029775
telemt_connections_current 4316
telemt_connections_me_current 4316
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 232059
telemt_upstream_connect_attempt_total 78259
telemt_upstream_connect_success_total 77698
telemt_upstream_connect_fail_total 490
telemt_upstream_connect_attempts_per_request{bucket="1"} 78188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43293
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31525
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1971
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 490
telemt_me_reconnect_attempts_total 6654
telemt_me_reconnect_success_total 1587
telemt_me_reader_eof_total 1408
telemt_me_idle_close_by_peer_total 1408
telemt_me_seq_mismatch_total 67
telemt_me_route_drop_no_conn_total 3541924
telemt_me_route_drop_channel_closed_total 282
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6979437
telemt_me_endpoint_quarantine_total 1094
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1069
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
telemt_me_writers_active_current 47
telemt_desync_total 31108
telemt_desync_full_logged_total 10199
telemt_desync_suppressed_total 20909
telemt_desync_frames_bucket_total{bucket="1_2"} 7682
telemt_desync_frames_bucket_total{bucket="3_10"} 11546
telemt_desync_frames_bucket_total{bucket="gt_10"} 11880
telemt_pool_swap_total 153
telemt_pool_force_close_total 4179
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 521
telemt_me_draining_writers_reap_progress_total 47131
telemt_me_writer_removed_unexpected_total 1427
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4592
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44030
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3866
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 313
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42952
telemt_me_writer_teardown_success_total{mode="normal"} 48622
telemt_me_writer_teardown_noop_total 47135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95757
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.080371
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95757
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 521
telemt_me_refill_failed_total 291
telemt_me_writer_restored_same_endpoint_total 1237
telemt_me_writer_restored_fallback_total 91
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 6987115
telemt_user_connections_current{user="hello"} 4316
telemt_user_octets_from_client{user="hello"} 125074955397 (116.49 GB)
telemt_user_octets_to_client{user="hello"} 2862761175699 (2.60 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1627
telemt_user_unique_ips_recent_window{user="hello"} 604
```