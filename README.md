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

# Server Metrics 2026-03-22 08:38:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 41539.3 (11h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 987503
telemt_connections_bad_total 57085
telemt_connections_current 1622
telemt_connections_me_current 1622
telemt_handshake_timeouts_total 45828
telemt_upstream_connect_attempt_total 16542
telemt_upstream_connect_success_total 16541
telemt_upstream_connect_attempts_per_request{bucket="1"} 16541
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10739
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 38
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 479
telemt_me_reconnect_success_total 253
telemt_me_reader_eof_total 251
telemt_me_idle_close_by_peer_total 251
telemt_me_route_drop_no_conn_total 552557
telemt_me_route_drop_channel_closed_total 176
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 821389
telemt_me_endpoint_quarantine_total 299
telemt_me_single_endpoint_shadow_rotate_total 335
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
telemt_me_writers_active_current 43
telemt_desync_total 6141
telemt_desync_full_logged_total 1723
telemt_desync_suppressed_total 4418
telemt_desync_frames_bucket_total{bucket="1_2"} 1876
telemt_desync_frames_bucket_total{bucket="3_10"} 2307
telemt_desync_frames_bucket_total{bucket="gt_10"} 1958
telemt_pool_swap_total 46
telemt_pool_force_close_total 1268
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 144
telemt_me_draining_writers_reap_progress_total 15012
telemt_me_writer_removed_unexpected_total 248
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1037
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14174
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1242
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 26
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13744
telemt_me_writer_teardown_success_total{mode="normal"} 15211
telemt_me_writer_teardown_noop_total 15014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30225
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 49.861642
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30225
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 144
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 231
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 819871
telemt_user_connections_current{user="hello"} 1622
telemt_user_octets_from_client{user="hello"} 11772646960 (10.96 GB)
telemt_user_octets_to_client{user="hello"} 264053047308 (245.92 GB)
telemt_user_unique_ips_current{user="hello"} 620
telemt_user_unique_ips_recent_window{user="hello"} 252
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 54905.3 (15h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1499047
telemt_connections_bad_total 148238
telemt_connections_current 1649
telemt_connections_me_current 1649
telemt_handshake_timeouts_total 42619
telemt_upstream_connect_attempt_total 28702
telemt_upstream_connect_success_total 28277
telemt_upstream_connect_fail_total 373
telemt_upstream_connect_attempts_per_request{bucket="1"} 28650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14229
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13987
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 373
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 2463
telemt_me_reconnect_success_total 1061
telemt_me_reader_eof_total 963
telemt_me_idle_close_by_peer_total 963
telemt_me_route_drop_no_conn_total 672692
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1129906
telemt_me_endpoint_quarantine_total 480
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 435
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_desync_total 4997
telemt_desync_full_logged_total 2896
telemt_desync_suppressed_total 2101
telemt_desync_frames_bucket_total{bucket="1_2"} 1083
telemt_desync_frames_bucket_total{bucket="3_10"} 1945
telemt_desync_frames_bucket_total{bucket="gt_10"} 1969
telemt_pool_swap_total 56
telemt_pool_force_close_total 1551
telemt_me_writer_close_signal_drop_total 128
telemt_me_draining_writers_reap_progress_total 22455
telemt_me_writer_removed_unexpected_total 933
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2198
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21179
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1427
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 124
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20904
telemt_me_writer_teardown_success_total{mode="normal"} 23377
telemt_me_writer_teardown_noop_total 22455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45832
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.093143
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45832
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 128
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 859
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 1131470
telemt_user_connections_current{user="hello"} 1649
telemt_user_octets_from_client{user="hello"} 17507704210 (16.31 GB)
telemt_user_octets_to_client{user="hello"} 391849775619 (364.94 GB)
telemt_user_msgs_from_client{user="hello"} 6406
telemt_user_msgs_to_client{user="hello"} 10605
telemt_user_unique_ips_current{user="hello"} 1071
telemt_user_unique_ips_recent_window{user="hello"} 563
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 129765.2 (36h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9737543
telemt_connections_bad_total 875962
telemt_connections_current 4971
telemt_connections_me_current 4971
telemt_handshake_timeouts_total 291686
telemt_upstream_connect_attempt_total 47899
telemt_upstream_connect_success_total 47819
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 47827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26024
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1913
telemt_me_reconnect_success_total 986
telemt_me_reader_eof_total 996
telemt_me_idle_close_by_peer_total 996
telemt_me_route_drop_no_conn_total 5474284
telemt_me_route_drop_channel_closed_total 81
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7642855
telemt_me_endpoint_quarantine_total 815
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 972
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
telemt_me_writers_active_current 43
telemt_desync_total 33142
telemt_desync_full_logged_total 10899
telemt_desync_suppressed_total 22243
telemt_desync_frames_bucket_total{bucket="1_2"} 7280
telemt_desync_frames_bucket_total{bucket="3_10"} 12867
telemt_desync_frames_bucket_total{bucket="gt_10"} 12995
telemt_pool_swap_total 140
telemt_pool_force_close_total 4633
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 708
telemt_me_draining_writers_reap_progress_total 43686
telemt_me_writer_removed_unexpected_total 957
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3678
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40441
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4319
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 314
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39053
telemt_me_writer_teardown_success_total{mode="normal"} 44119
telemt_me_writer_teardown_noop_total 43730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87849
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 185.319791
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87849
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 708
telemt_me_refill_failed_total 49
telemt_me_writer_restored_same_endpoint_total 884
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 7633089
telemt_user_connections_current{user="hello"} 4971
telemt_user_octets_from_client{user="hello"} 125921629968 (117.27 GB)
telemt_user_octets_to_client{user="hello"} 2548002296944 (2.32 TB)
telemt_user_unique_ips_current{user="hello"} 1997
telemt_user_unique_ips_recent_window{user="hello"} 648
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 129766.5 (36h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7942791
telemt_connections_bad_total 710978
telemt_connections_current 4017
telemt_connections_me_current 4017
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 255271
telemt_upstream_connect_attempt_total 53916
telemt_upstream_connect_success_total 53438
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 53684
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26068
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26139
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1123
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2896
telemt_me_reconnect_success_total 1089
telemt_me_reader_eof_total 1006
telemt_me_idle_close_by_peer_total 1006
telemt_me_route_drop_no_conn_total 2662687
telemt_me_route_drop_channel_closed_total 319
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5874035
telemt_me_endpoint_quarantine_total 828
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 1003
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 41
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 26797
telemt_desync_full_logged_total 9171
telemt_desync_suppressed_total 17626
telemt_desync_frames_bucket_total{bucket="1_2"} 6445
telemt_desync_frames_bucket_total{bucket="3_10"} 10373
telemt_desync_frames_bucket_total{bucket="gt_10"} 9979
telemt_pool_swap_total 142
telemt_pool_force_close_total 4216
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 454
telemt_me_draining_writers_reap_progress_total 41899
telemt_me_writer_removed_unexpected_total 1027
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3577
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39262
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3965
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 251
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37683
telemt_me_writer_teardown_success_total{mode="normal"} 42839
telemt_me_writer_teardown_noop_total 41905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84744
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 57.387521
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84744
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 454
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 918
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 206
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 5796672
telemt_user_connections_current{user="hello"} 4017
telemt_user_octets_from_client{user="hello"} 160657351815 (149.62 GB)
telemt_user_octets_to_client{user="hello"} 2784570804562 (2.53 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1702
telemt_user_unique_ips_recent_window{user="hello"} 552
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 129730.7 (36h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7640971
telemt_connections_bad_total 633600
telemt_connections_current 3725
telemt_connections_me_current 3725
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 253386
telemt_upstream_connect_attempt_total 58319
telemt_upstream_connect_success_total 57642
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 57789
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27104
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 930
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1310
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 2840
telemt_me_reconnect_success_total 1219
telemt_me_reader_eof_total 1119
telemt_me_idle_close_by_peer_total 1119
telemt_me_route_drop_no_conn_total 3069794
telemt_me_route_drop_channel_closed_total 187
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5696300
telemt_me_endpoint_quarantine_total 913
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 956
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
telemt_me_writers_active_current 42
telemt_desync_total 26768
telemt_desync_full_logged_total 9094
telemt_desync_suppressed_total 17674
telemt_desync_frames_bucket_total{bucket="1_2"} 6473
telemt_desync_frames_bucket_total{bucket="3_10"} 10262
telemt_desync_frames_bucket_total{bucket="gt_10"} 10033
telemt_pool_swap_total 139
telemt_pool_force_close_total 4115
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 480
telemt_me_draining_writers_reap_progress_total 42894
telemt_me_writer_removed_unexpected_total 1130
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3818
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40190
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3802
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 313
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38779
telemt_me_writer_teardown_success_total{mode="normal"} 44008
telemt_me_writer_teardown_noop_total 42906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86914
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 46.181053
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86914
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 480
telemt_me_refill_failed_total 88
telemt_me_writer_restored_same_endpoint_total 1056
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 5689355
telemt_user_connections_current{user="hello"} 3725
telemt_user_octets_from_client{user="hello"} 147860116323 (137.71 GB)
telemt_user_octets_to_client{user="hello"} 2528789539631 (2.30 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1529
telemt_user_unique_ips_recent_window{user="hello"} 549
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 15.3 (0h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_upstream_connect_attempt_total 64
telemt_upstream_connect_success_total 59
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 64
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 129737.3 (36h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7272644
telemt_connections_bad_total 659500
telemt_connections_current 3093
telemt_connections_direct_current 127
telemt_connections_me_current 2966
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 149370
telemt_upstream_connect_attempt_total 66910
telemt_upstream_connect_success_total 66102
telemt_upstream_connect_fail_total 676
telemt_upstream_connect_attempts_per_request{bucket="1"} 66778
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37721
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28012
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 368
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 676
telemt_me_reconnect_attempts_total 70273
telemt_me_reconnect_success_total 1996
telemt_me_reader_eof_total 1757
telemt_me_idle_close_by_peer_total 1756
telemt_me_route_drop_no_conn_total 2851883
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 40
telemt_me_route_drop_queue_full_profile_total{profile="high"} 40
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5713462
telemt_me_endpoint_quarantine_total 876
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 980
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
telemt_me_writers_active_current 38
telemt_desync_total 28827
telemt_desync_full_logged_total 10022
telemt_desync_suppressed_total 18805
telemt_desync_frames_bucket_total{bucket="1_2"} 5755
telemt_desync_frames_bucket_total{bucket="3_10"} 11100
telemt_desync_frames_bucket_total{bucket="gt_10"} 11972
telemt_pool_swap_total 136
telemt_pool_force_close_total 3897
telemt_pool_stale_pick_total 66
telemt_me_writer_close_signal_drop_total 462
telemt_me_draining_writers_reap_progress_total 45042
telemt_me_writer_removed_unexpected_total 1787
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4533
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42322
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3462
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 435
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41145
telemt_me_writer_teardown_success_total{mode="normal"} 46855
telemt_me_writer_teardown_noop_total 45043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91898
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.362398
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91898
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 462
telemt_me_refill_failed_total 4226
telemt_me_writer_restored_same_endpoint_total 1657
telemt_me_writer_restored_fallback_total 40
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7319
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 5704060
telemt_user_connections_current{user="hello"} 3093
telemt_user_octets_from_client{user="hello"} 144134927440 (134.24 GB)
telemt_user_octets_to_client{user="hello"} 2365220985418 (2.15 TB)
telemt_user_msgs_from_client{user="hello"} 78077
telemt_user_msgs_to_client{user="hello"} 338997
telemt_user_unique_ips_current{user="hello"} 1353
telemt_user_unique_ips_recent_window{user="hello"} 586
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 66573.6 (18h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5712382
telemt_connections_bad_total 224719
telemt_connections_current 4528
telemt_connections_me_current 4528
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2267712
telemt_upstream_connect_attempt_total 35807
telemt_upstream_connect_success_total 35557
telemt_upstream_connect_fail_total 243
telemt_upstream_connect_attempts_per_request{bucket="1"} 35800
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21120
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14347
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 243
telemt_me_reconnect_attempts_total 47367
telemt_me_reconnect_success_total 1175
telemt_me_reader_eof_total 846
telemt_me_idle_close_by_peer_total 846
telemt_me_route_drop_no_conn_total 1429660
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2865364
telemt_me_endpoint_quarantine_total 459
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 13
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 508
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
telemt_me_writers_active_current 52
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 15546
telemt_desync_full_logged_total 5287
telemt_desync_suppressed_total 10259
telemt_desync_frames_bucket_total{bucket="1_2"} 3048
telemt_desync_frames_bucket_total{bucket="3_10"} 5974
telemt_desync_frames_bucket_total{bucket="gt_10"} 6524
telemt_pool_swap_total 71
telemt_pool_force_close_total 2124
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 199
telemt_me_draining_writers_reap_progress_total 23962
telemt_me_writer_removed_unexpected_total 916
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2061
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22839
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1852
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 272
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21838
telemt_me_writer_teardown_success_total{mode="normal"} 24900
telemt_me_writer_teardown_noop_total 23968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48868
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.526143
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48868
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 199
telemt_me_refill_failed_total 2687
telemt_me_writer_restored_same_endpoint_total 1048
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 2866562
telemt_user_connections_current{user="hello"} 4528
telemt_user_octets_from_client{user="hello"} 73477678108 (68.43 GB)
telemt_user_octets_to_client{user="hello"} 1254903159738 (1.14 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1902
telemt_user_unique_ips_recent_window{user="hello"} 952
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 47544.2 (13h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 416197
telemt_connections_bad_total 2903
telemt_connections_current 1041
telemt_connections_me_current 1041
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 8365
telemt_upstream_connect_attempt_total 25376
telemt_upstream_connect_success_total 25317
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 25371
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13153
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 245
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_reconnect_attempts_total 1007
telemt_me_reconnect_success_total 383
telemt_me_reader_eof_total 377
telemt_me_idle_close_by_peer_total 377
telemt_me_route_drop_no_conn_total 131266
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 375907
telemt_me_endpoint_quarantine_total 446
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 408
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
telemt_me_writers_active_current 91
telemt_desync_total 1728
telemt_desync_full_logged_total 507
telemt_desync_suppressed_total 1221
telemt_desync_frames_bucket_total{bucket="1_2"} 512
telemt_desync_frames_bucket_total{bucket="3_10"} 681
telemt_desync_frames_bucket_total{bucket="gt_10"} 535
telemt_pool_swap_total 51
telemt_pool_force_close_total 1142
telemt_me_writer_close_signal_drop_total 43
telemt_me_draining_writers_reap_progress_total 20335
telemt_me_writer_removed_unexpected_total 362
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1427
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19285
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1139
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19193
telemt_me_writer_teardown_success_total{mode="normal"} 20712
telemt_me_writer_teardown_noop_total 20335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41047
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.836601
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41047
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 43
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 332
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 378103
telemt_user_connections_current{user="hello"} 1041
telemt_user_octets_from_client{user="hello"} 7296380797 (6.80 GB)
telemt_user_octets_to_client{user="hello"} 195896889183 (182.44 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 351
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 129741.9 (36h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8961899
telemt_connections_bad_total 1034532
telemt_connections_current 4889
telemt_connections_me_current 4889
telemt_handshake_timeouts_total 247732
telemt_upstream_connect_attempt_total 50494
telemt_upstream_connect_success_total 50301
telemt_upstream_connect_fail_total 149
telemt_upstream_connect_attempts_per_request{bucket="1"} 50450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25362
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 149
telemt_me_reconnect_attempts_total 1894
telemt_me_reconnect_success_total 1027
telemt_me_reader_eof_total 999
telemt_me_idle_close_by_peer_total 999
telemt_me_route_drop_no_conn_total 2508229
telemt_me_route_drop_channel_closed_total 60
telemt_me_route_drop_queue_full_total 25
telemt_me_route_drop_queue_full_profile_total{profile="high"} 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6634202
telemt_me_endpoint_quarantine_total 922
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 985
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
telemt_me_writers_active_current 45
telemt_desync_total 26631
telemt_desync_full_logged_total 8743
telemt_desync_suppressed_total 17888
telemt_desync_frames_bucket_total{bucket="1_2"} 6579
telemt_desync_frames_bucket_total{bucket="3_10"} 9706
telemt_desync_frames_bucket_total{bucket="gt_10"} 10346
telemt_pool_swap_total 144
telemt_pool_force_close_total 3842
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 468
telemt_me_draining_writers_reap_progress_total 45545
telemt_me_writer_removed_unexpected_total 959
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3631
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42903
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3741
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 101
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41703
telemt_me_writer_teardown_success_total{mode="normal"} 46534
telemt_me_writer_teardown_noop_total 45547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92081
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.878521
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92081
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 468
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 899
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 6607300
telemt_user_connections_current{user="hello"} 4889
telemt_user_octets_from_client{user="hello"} 129221741996 (120.35 GB)
telemt_user_octets_to_client{user="hello"} 3110208483012 (2.83 TB)
telemt_user_unique_ips_current{user="hello"} 1860
telemt_user_unique_ips_recent_window{user="hello"} 659
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 129738.9 (36h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7786171
telemt_connections_bad_total 864872
telemt_connections_current 4427
telemt_connections_me_current 4427
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 207480
telemt_upstream_connect_attempt_total 66527
telemt_upstream_connect_success_total 66012
telemt_upstream_connect_fail_total 448
telemt_upstream_connect_attempts_per_request{bucket="1"} 66460
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37838
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27026
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 630
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 448
telemt_me_reconnect_attempts_total 6387
telemt_me_reconnect_success_total 1456
telemt_me_reader_eof_total 1307
telemt_me_idle_close_by_peer_total 1307
telemt_me_seq_mismatch_total 61
telemt_me_route_drop_no_conn_total 2643588
telemt_me_route_drop_channel_closed_total 227
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5923872
telemt_me_endpoint_quarantine_total 1016
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 983
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
telemt_desync_total 25489
telemt_desync_full_logged_total 8481
telemt_desync_suppressed_total 17008
telemt_desync_frames_bucket_total{bucket="1_2"} 6277
telemt_desync_frames_bucket_total{bucket="3_10"} 9379
telemt_desync_frames_bucket_total{bucket="gt_10"} 9833
telemt_pool_swap_total 141
telemt_pool_force_close_total 3788
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 461
telemt_me_draining_writers_reap_progress_total 44177
telemt_me_writer_removed_unexpected_total 1322
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4230
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41331
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3517
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 271
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40389
telemt_me_writer_teardown_success_total{mode="normal"} 45561
telemt_me_writer_teardown_noop_total 44181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89742
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.812183
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89742
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 461
telemt_me_refill_failed_total 285
telemt_me_writer_restored_same_endpoint_total 1140
telemt_me_writer_restored_fallback_total 84
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 112
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 5924878
telemt_user_connections_current{user="hello"} 4427
telemt_user_octets_from_client{user="hello"} 109040568685 (101.55 GB)
telemt_user_octets_to_client{user="hello"} 2558160338780 (2.33 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1801
telemt_user_unique_ips_recent_window{user="hello"} 627
```